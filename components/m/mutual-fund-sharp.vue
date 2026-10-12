<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="b0xugtbht"/><path class="d57bwhdjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mutual-fund-sharp" /></template>
<style>
.b0xugtbht {
  cx: 5.5px;
  cy: 7.75px;
  r: 2.25px;
}

.d57bwhdjf {
  d: path("M10.75 3.5h3.5V10h-3.5zm6.5 6.5V6.25H21V10Zm-13 3h15.5l1.276.001l-.306 1.239l-1.25 5.1l-.464 1.91H4.994l-.464-1.91l-1.25-5.1l-.306-1.239z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
