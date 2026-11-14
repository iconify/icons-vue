<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ejdrbz_hn"/><path class="st_k70qzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:plant-wall-frame" /></template>
<style>
.ejdrbz_hn {
  d: path("M5.625 5h12.75A2.625 2.625 0 0 1 21 7.625v10.25a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 17.875V7.625A2.625 2.625 0 0 1 5.625 5M8.5 5L12 2.5L15.5 5M12 17.5V10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.st_k70qzo {
  d: path("M12 17c0-3-2.5-5-5-5c0 3 2.5 5 5 5m0-3.5c0-3 2.5-5 5-5c0 3-2.5 5-5 5");
}

</style>
