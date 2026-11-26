<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv-31s0bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:zodiac-scorpio-sharp" /></template>
<style>
.zv-31s0bw {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 16L2 6C2 4.3431 3.3431 3 5 3C6.6569 3 8 4.3431 8 6L8 16M8 6C8 4.3431 9.3431 3 11 3C12.6569 3 14 4.3431 14 6L14 14C14 15.6569 15.3431 17 17 17L22 17M17.7071 12.7071L22 17L17.7071 21.2929");
}

</style>
