<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxf8w4bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ratio-21-9" /></template>
<style>
.uxf8w4bro {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 10C2 8.8954 2.8954 8 4 8L20 8C21.1046 8 22 8.8954 22 10L22 14C22 15.1046 21.1046 16 20 16L4 16C2.8954 16 2 15.1046 2 14L2 10Z");
}

</style>
