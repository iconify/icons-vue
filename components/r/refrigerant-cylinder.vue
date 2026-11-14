<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="saev_6b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:refrigerant-cylinder" /></template>
<style>
.saev_6b9f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.5V11a5 5 0 0 1 10 0v10.5Zm5-19V6M6 2.5h5m8 13v6M16.5 17l5 3m-5 0l5-3");
}

</style>
