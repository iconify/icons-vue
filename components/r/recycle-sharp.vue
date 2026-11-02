<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnjut0b4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:recycle-sharp" /></template>
<style>
.nnjut0b4v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 5.598L12 3l5.06 8.765m-4.098-1.098l4.098 1.098l1.098-4.098m1.002 7.735L20.66 18H10.54m3-3l-3 3l3 3m-7.2-3h-3L8.4 9.235m1.098 4.098L8.4 9.235l-4.098 1.098");
}

</style>
