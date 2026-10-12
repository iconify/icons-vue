<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="j46ti1eoh"/><circle class="e6m1jbc1y"/><path class="eswozbbij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:steering-rack-sharp" /></template>
<style>
.e6m1jbc1y {
  cx: 12px;
  cy: 7.25px;
  r: 2.25px;
}

.eswozbbij {
  d: path("M12 5V2.75");
}

.j46ti1eoh {
  d: path("M4.5 13.5h15V18h-15zm3 0V15m3-1.5V15m3-1.5V15m3-1.5V15m-12 .75H2.75m16.75 0h1.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
