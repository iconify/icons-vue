<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqt5xnsdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:usb-stick-plus" /></template>
<style>
.qqt5xnsdn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 9h3a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-3A3.5 3.5 0 0 1 7 18v-5.5A3.5 3.5 0 0 1 10.5 9m-.25-6.5h3.5a1.75 1.75 0 0 1 1.75 1.75v3A1.75 1.75 0 0 1 13.75 9h-3.5A1.75 1.75 0 0 1 8.5 7.25v-3a1.75 1.75 0 0 1 1.75-1.75m.5 3.25h2.5M12 13v5m-2.5-2.5h5");
}

</style>
