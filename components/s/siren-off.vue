<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mzb4uz-mr"/><path class="evympl59y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:siren-off" /></template>
<style>
.evympl59y {
  d: path("M12 10.5A2.5 2.5 0 0 0 9.5 13v1.5M12 2.75V5m-6.75.25l1.5 1.5m12-1.5l-1.5 1.5M2.75 12h1.5m15.5 0h1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mzb4uz-mr {
  d: path("M7 17.5V13a5 5 0 0 1 10 0v4.5h1.75a1 1 0 0 1 1 1V20a1 1 0 0 1-1 1H5.25a1 1 0 0 1-1-1v-1.5a1 1 0 0 1 1-1Zm0 0h10");
}

</style>
