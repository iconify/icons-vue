<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds8hlw7hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rail-yard-sharp" /></template>
<style>
.ds8hlw7hj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5h10m-10 7h18.5m-18.5 7h18.5M5.75 5l7 7m-.5 0l7 7M14 3h7.25v4H14z");
}

</style>
