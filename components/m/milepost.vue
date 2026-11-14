<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btescfqgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:milepost" /></template>
<style>
.btescfqgv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.125 5h9.75A2.625 2.625 0 0 1 19.5 7.625v1.75A2.625 2.625 0 0 1 16.875 12h-9.75A2.625 2.625 0 0 1 4.5 9.375v-1.75A2.625 2.625 0 0 1 7.125 5M9.5 5V2.5h5V5m-5 7v9.5m5-9.5v9.5M8 8.5h8");
}

</style>
