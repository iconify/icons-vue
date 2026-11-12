<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n8lh2jbfb"/><path class="q0auevbwe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:passkey-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.n8lh2jbfb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 7a5 5 0 1 1 10.001.001A5 5 0 0 1 3 7m10 15H3a1 1 0 0 1-1-1a8 8 0 0 1 .45-2.668C3.295 15.937 5.357 14.001 8 14c2.643.001 4.705 1.937 5.55 4.332c.301.857.453 1.76.45 2.668a1 1 0 0 1-1 1");
}

.q0auevbwe {
  d: path("M16 13a1 1 0 0 1 0-2a1 1 0 0 1 0-2h3a1 1 0 0 1 1 1v6.171a3 3 0 1 1-2 0V13ZM2 21a8 8 0 0 1 .45-2.668C3.295 15.937 5.357 14.001 8 14c1.7 0 3.227.826 4.304 2.117C13.435 17.475 14 19.243 14 21a1 1 0 0 1-2 0a6 6 0 0 0-.336-2.003C11.107 17.417 9.775 16 8 16s-3.107 1.417-3.664 2.997A6 6 0 0 0 4 21a1 1 0 0 1-2 0m16.999-3a1.001 1.001 0 1 0 .002 2.002A1.001 1.001 0 0 0 19 18Z");
}

</style>
