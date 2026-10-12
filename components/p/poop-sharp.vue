<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="o17ah726s"/><path class="b9mcxsbuu"/><path class="r9g2qtbns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:poop-sharp" /></template>
<style>
.b9mcxsbuu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 13.75h.01m4.49 0h.01");
}

.o17ah726s {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 21.25h11.5a2.75 2.75 0 0 0 .5-5.45a2.5 2.5 0 0 0-1.5-4.8a3.25 3.25 0 0 0-3.5-4.25l.917-2.292L11.75 3.25c.25 1.5-1 2.5-2.5 2.75a3 3 0 0 0-2 5a2.5 2.5 0 0 0-1.5 4.8a2.75 2.75 0 0 0 .5 5.45Z");
}

.r9g2qtbns {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 17.75L12 18.955l2.25-1.205");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
