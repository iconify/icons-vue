<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hg_spz4qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reflex-hammer" /></template>
<style>
.hg_spz4qj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 20.5l9.6-9.6m5.11 1.97l-.34.34q-1.24 1.24-2.48 0l-4.6-4.6q-1.24-1.24 0-2.48l.34-.34q1.24-1.24 2.48 0l4.6 4.6q1.24 1.24 0 2.48");
}

</style>
