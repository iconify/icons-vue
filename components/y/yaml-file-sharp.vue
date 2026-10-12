<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="s43l187bp"/><path class="s1ovipb_d"/><path class="r4rqh8jfq"/><path class="lxubsttwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:yaml-file-sharp" /></template>
<style>
.lxubsttwt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 14.5h.01m1.99 0h3m-5 3h.01m1.99 0h3");
}

.r4rqh8jfq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.75 11.25h.01");
}

.s1ovipb_d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 2.75v5.5h5.5m-10.5 3h3");
}

.s43l187bp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 2.75h-9v18.5h14.5v-13Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
