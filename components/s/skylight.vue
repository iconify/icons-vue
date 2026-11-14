<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1-ve0btl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:skylight" /></template>
<style>
.o1-ve0btl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.625 8h10.75A2.625 2.625 0 0 1 20 10.625v6.75A2.625 2.625 0 0 1 17.375 20H6.625A2.625 2.625 0 0 1 4 17.375v-6.75A2.625 2.625 0 0 1 6.625 8M12 8v12m-8-6h16M7.5 3L6 5m6-2.5V5m4.5-2L18 5");
}

</style>
