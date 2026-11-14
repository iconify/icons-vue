<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ftrf-_2jh"/><path class="fkqzdw5-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:parcel-locker" /></template>
<style>
.fkqzdw5-d {
  d: path("m17.098 3.412l2.75 1.196a1.5 1.5 0 0 1 .902 1.375v12.034a1.5 1.5 0 0 1-.902 1.375l-2.75 1.196A1.5 1.5 0 0 1 15 19.212V4.788a1.5 1.5 0 0 1 2.098-1.376M7 11.5h4a1.5 1.5 0 0 1 1.5 1.5v3.5A1.5 1.5 0 0 1 11 18H7a1.5 1.5 0 0 1-1.5-1.5V13A1.5 1.5 0 0 1 7 11.5m-1.5 2.25h7M9 11.5v2.25M19 12h.01");
}

.ftrf-_2jh {
  d: path("M5.625 2.5h6.75A2.625 2.625 0 0 1 15 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625h-6.75A2.625 2.625 0 0 1 3 18.875V5.125A2.625 2.625 0 0 1 5.625 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
