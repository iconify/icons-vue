<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="x88mwabma"/><path class="t2zvjcbsg"/><path class="rhj7-w4rz"/><path class="tgipa-jqd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stud-finder-sharp" /></template>
<style>
.rhj7-w4rz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 18.5h.01");
}

.t2zvjcbsg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 13.25h6.5v2.5h-6.5Z");
}

.tgipa-jqd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.17 6.67L12 3.837l2.83 2.833m-7.6-1.94a6.75 6.75 0 0 1 9.54 0");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.x88mwabma {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 10h13.5v11.25H5.25z");
}

</style>
