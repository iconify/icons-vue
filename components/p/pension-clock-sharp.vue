<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="a-it-3beh"/><path class="u7n8e3bvt"/><circle class="ygphxfbhc"/><path class="yi4q6cbjg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pension-clock-sharp" /></template>
<style>
.a-it-3beh {
  d: path("M18.25 10.32a7.75 7.75 0 1 0-7.93 7.93a7 7 0 0 1 7.93-7.93Z");
}

.u7n8e3bvt {
  d: path("M10.5 6.25v4.25H7");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ygphxfbhc {
  cx: 17.25px;
  cy: 17.25px;
  r: 4px;
}

.yi4q6cbjg {
  d: path("m18.38 16.27l-.35-.75h-1.94v.86c0 1.22 2.34.61 2.34 1.78v.83h-2.018l-.292-.73");
}

</style>
