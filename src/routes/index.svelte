<script context="module" lang="ts">
	import type { Load } from '@sveltejs/kit';

	const YOUTUBE_URL = 'https://www.youtube.com/channel/UCUqcGXhbJGakSs0YG-xF5fg';

	export const load: Load = () => {
		return {
			status: 302,
			redirect: YOUTUBE_URL
		};
	};
</script>
