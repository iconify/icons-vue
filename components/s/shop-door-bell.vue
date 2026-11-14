<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bq713uoow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shop-door-bell" /></template>
<style>
.bq713uoow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 16c0-6.5 2-9.5 5-9.5s5 3 5 9.5Zm-2.5 0h15M12 3v3.5m0 12.75h.01");
}

</style>
