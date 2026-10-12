<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="r8ny-mbmd"/><path class="zzlulxbck"/><path class="wr0qklbqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:smart-home-sharp" /></template>
<style>
.r8ny-mbmd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 9.75L12 3.25l8.25 6.5v10.5H3.75v-2Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wr0qklbqh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.25 14.75h.01");
}

.zzlulxbck {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 12.5h4.5a2.25 2.25 0 0 1 0 4.5h-4.5a2.25 2.25 0 0 1 0-4.5Z");
}

</style>
