<script lang="ts">
	import { page } from "$app/stores";
	import { env as envPublic } from "$env/dynamic/public";
	import { base } from "$app/paths";

	export let classNames = "";
</script>
<img
	class={classNames}
	alt="{envPublic.PUBLIC_APP_NAME} logo"
  src="{envPublic.PUBLIC_ORIGIN || $page.url.origin}{base}/chatui/logo.png"
/>
