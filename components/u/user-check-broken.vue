<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="a8neukw-z"/><path class="olic4gb-u"/><path class="x3z2s0btf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-check-broken" /></template>
<style>
.a8neukw-z {
  cx: 11px;
  cy: 6px;
  r: 4px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.olic4gb-u {
  stroke-linejoin: round;
  d: path("M17 10.3L18.3333 11.5L21 8.5");
}

.x3z2s0btf {
  d: path("M18.9975 18C19 17.8358 19 17.669 19 17.5C19 15.0147 15.4183 13 11 13C6.58172 13 3 15.0147 3 17.5C3 19.9853 3 22 11 22C13.231 22 14.8398 21.8433 16 21.5634");
}

</style>
