<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="e5w3lvb2t"/><path class="xo54ktoll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sleet-sharp" /></template>
<style>
.e5w3lvb2t {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.51 13.89a3.52 3.52 0 0 1-.49-7.01a5.06 5.06 0 0 1 9.38-1.22a3.96 3.96 0 0 1-.53 8.23ZM8.5 17l-1.25 4.25M17 17l-1.25 4.25");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xo54ktoll {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.75 17.5h.01m-1.01 3.25h.01");
}

</style>
