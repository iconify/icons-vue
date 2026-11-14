<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lqb7eybmr"/><path class="dmefz13ah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:medal-bronze" /></template>
<style>
.dmefz13ah {
  d: path("M10 12.5h4l-2 2.25c1.25 0 2 .75 2 1.75s-.9 1.75-2 1.75c-1 0-1.75-.4-2-1");
}

.lqb7eybmr {
  d: path("M6 15a6 6 0 1 0 12 0a6 6 0 1 0-12 0ZM7.5 2.5l2.75 6.75M16.5 2.5l-2.75 6.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
