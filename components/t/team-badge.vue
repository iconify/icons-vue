<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kr6grkbdu"/><path class="y5hh2fbrb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:team-badge" /></template>
<style>
.kr6grkbdu {
  d: path("m12 2.5l7.5 3V11c0 5-3.5 8.5-7.5 10.5c-4-2-7.5-5.5-7.5-10.5V5.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y5hh2fbrb {
  d: path("m12 7.75l1 2.5h2.5l-2 1.75l.75 2.5L12 13l-2.25 1.5l.75-2.5l-2-1.75H11Z");
}

</style>
