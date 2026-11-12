<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rwp5pobhv"/><path class="dj9zaictl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:transfer-vertical-broken" /></template>
<style>
.dj9zaictl {
  d: path("M4 14.5L10 20V10M10 4L10 6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rwp5pobhv {
  d: path("M20 9.5L14 4V14M14 20L14 17.5");
}

</style>
