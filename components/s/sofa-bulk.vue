<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e3ceykbuz"/><path class="rsufbacoc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sofa-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e3ceykbuz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 11a2.999 2.999 0 0 1 5.121-2.121c.274.273.493.596.643.953c.157.369.237.767.236 1.168a.997.997 0 0 0 1 1h6a.997.997 0 0 0 1-1a3 3 0 0 1 .236-1.168A2.998 2.998 0 0 1 22 11v4a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.rsufbacoc {
  d: path("M7 4h10a3.004 3.004 0 0 1 3 3v2a1 1 0 0 1-2 0V7a1 1 0 0 0-1-1h-4v7a1 1 0 0 1-2 0V6H7l-.05.001h-.001A.984.984 0 0 0 6 7v2a1 1 0 0 1-2 0V6.999A3 3 0 0 1 7 4M6 19a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Zm14 0a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

</style>
