<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yi2hin2-n"/><path class="nxfv68bbc"/><path class="a7at53t5l"/><path class="cn1ca2bxs"/><path class="g6dxy8b1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plug-broken" /></template>
<style>
.a7at53t5l {
  d: path("M9.25 2V7.5");
}

.cn1ca2bxs {
  d: path("M14.75 2V7.5");
}

.g6dxy8b1m {
  d: path("M12 18.25V22");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nxfv68bbc {
  d: path("M9.75 15.062V16.9999C9.75 17.7999 10.3 18.2499 11.1 18.2499H12.9C13.7 18.2499 14.25 17.7999 14.25 16.9999V15.062");
}

.yi2hin2-n {
  d: path("M13.4 7.5H16.2C17.2 7.5 18 8.3 18 9.3V9.5C18 12.8137 15.3137 15.5 12 15.5C8.6863 15.5 6 12.8137 6 9.5V9.3C6 8.3 6.8 7.5 7.8 7.5H10.6");
}

</style>
