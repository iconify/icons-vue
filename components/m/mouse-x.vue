<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d52vxjunz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mouse-x" /></template>
<style>
.d52vxjunz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3za5.5 5.5 0 0 1 5.5 5.5v7A5.5 5.5 0 0 1 12 21a5.5 5.5 0 0 1-5.5-5.5v-7A5.5 5.5 0 0 1 12 3m0 3.5v3m-1.75 3l3.5 3.5m0-3.5l-3.5 3.5");
}

</style>
