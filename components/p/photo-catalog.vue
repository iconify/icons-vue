<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sms8-rbwy"/><path class="qb_u-9nqh"/><path class="hs4r6le7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:photo-catalog" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hs4r6le7p {
  d: path("M8 6.25V3.5h13.5v11h-2.75M5.5 17.25l3.5-4l3.5 4m.25-4.75h.01");
}

.qb_u-9nqh {
  d: path("M5.25 9V6.25h13.5v11H16");
}

.sms8-rbwy {
  d: path("M5.125 9h8.25A2.625 2.625 0 0 1 16 11.625v5.75A2.625 2.625 0 0 1 13.375 20h-8.25A2.625 2.625 0 0 1 2.5 17.375v-5.75A2.625 2.625 0 0 1 5.125 9");
}

</style>
