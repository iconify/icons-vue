<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yv0shlb-w"/><path class="fiz-p3b0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-minus-corner-duocolor" /></template>
<style>
.fiz-p3b0n {
  d: path("M12 4h6a2 2 0 0 1 2 2v3M9 20H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h6M4 9h16M4 15h5m3-11v5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yv0shlb-w {
  stroke-opacity: 0.4;
  d: path("M13 16h8");
}

</style>
