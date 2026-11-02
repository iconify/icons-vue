<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xmmcdfmqh"/><path class="wzjns0bqd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:vector-square-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.wzjns0bqd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 5h10m2 2v10m-2 2H7m-2-2V7M3 3h4v4H3Zm14 0h4v4h-4Zm0 14h4v4h-4ZM3 17h4v4H3Z");
}

.xmmcdfmqh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 5v2h2v10h-2v2H7v-2H5V7h2V5Z");
}

</style>
