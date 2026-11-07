<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r889qqats"/><path class="jq3u_r79v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-play-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jq3u_r79v {
  d: path("m12.147 7.282l2.256 1.58a1.997 1.997 0 0 1 0 3.276l-2.256 1.58A2 2 0 0 1 9 12.079V8.921a2 2 0 0 1 3.147-1.639M11 8.921v3.158l2.256-1.579ZM9 19h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

.r889qqats {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 8a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v5a5 5 0 0 1-5 5H8a5 5 0 0 1-5-5Z");
}

</style>
