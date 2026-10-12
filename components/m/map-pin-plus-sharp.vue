<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="q71tojf4b"/><path class="zs3o2ob7q"/><circle class="se8pm3_-l"/><path class="dxcm-ab6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:map-pin-plus-sharp" /></template>
<style>
.dxcm-ab6w {
  d: path("M8.5 21h7");
}

.q71tojf4b {
  cx: 12px;
  cy: 8.25px;
  r: 5.5px;
}

.se8pm3_-l {
  cx: 12px;
  cy: 8.25px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zs3o2ob7q {
  d: path("M12 13.75v4.75");
}

</style>
