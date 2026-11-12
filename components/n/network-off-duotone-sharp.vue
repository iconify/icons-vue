<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xbj15jb5q"/><path class="bpod1qjdi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-off-duotone-sharp" /></template>
<style>
.bpod1qjdi {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h3v3M3 16h6v5H3zm18 2v3h-6v-5h4M6 16v-4h9M5 2l17 17");
}

.ft5dv1b6b {
  fill: none;
}

.xbj15jb5q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 3h3v3ZM9 8V6l2 2Zm0 8v5H3v-5Zm12 5h-6v-5h4l2 2Z");
}

</style>
