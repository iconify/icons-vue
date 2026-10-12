<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-2v-6b_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sled-sharp" /></template>
<style>
.p-2v-6b_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 9.5h14.5V13H3.25zM6.5 13v5.25m8-5.25v5.25m-11.75 0h17.5V15m-2.5-3.75h3.5v-3.5");
}

</style>
