<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dd5-tybym"/><path class="v41tnfpvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-box-duotone" /></template>
<style>
.dd5-tybym {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16.5 14.467a.5.5 0 0 1-.279.448l-4 1.976a.5.5 0 0 1-.442 0l-4-1.976a.5.5 0 0 1-.279-.448V9.533a.5.5 0 0 1 .279-.448l4-1.976a.5.5 0 0 1 .442 0l4 1.976a.5.5 0 0 1 .279.448Z");
}

.ft5dv1b6b {
  fill: none;
}

.v41tnfpvx {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm13.5 7v2.467a.5.5 0 0 1-.279.448l-4 1.976a.5.5 0 0 1-.442 0l-4-1.976a.5.5 0 0 1-.279-.448V9.533a.5.5 0 0 1 .279-.448l4-1.976a.5.5 0 0 1 .442 0l4 1.976a.5.5 0 0 1 .279.448zM7.58 9.262L12 11.444l4.42-2.182M12 11.444v5.498");
}

</style>
