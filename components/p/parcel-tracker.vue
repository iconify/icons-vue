<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c4cmph81c"/><path class="z6c6bnbyy"/><path class="hz-lymq6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:parcel-tracker" /></template>
<style>
.c4cmph81c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.339 23.276v10.767l15.654 2.941V13.519");
}

.hz-lymq6d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.775 22.075l13.386 1.844a1.176 1.176 0 0 0 1.236-1.643l-3.835-8.632l-15.57-2.628L8.34 13.77l-3.73 8.016a1.176 1.176 0 0 0 1.149 1.67l13.338-.927a1.47 1.47 0 0 0 1.24-.865l3.655-8.144l3.653 7.727a1.47 1.47 0 0 0 1.129.828m-17.87 8.589l2.941.313");
}

.z6c6bnbyy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.562 23.561v10.294l-15.569 3.129");
}

</style>
