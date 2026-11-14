<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t68r2do9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:security-system" /></template>
<style>
.t68r2do9r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h19m-14 0V6a4.5 4.5 0 0 0 9 0V2.5M12 7h.01m5.132 5.128a8 8 0 0 1-10.284 0m12.025 3.702a12 12 0 0 1-13.766 0m14.633 3.593a15.5 15.5 0 0 1-15.5 0");
}

</style>
