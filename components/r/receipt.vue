<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrq1fjnhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:receipt" /></template>
<style>
.jrq1fjnhs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 9H12M8 13H16M4 5C4 3.34315 5.34315 2 7 2H17C18.6569 2 20 3.34315 20 5V20L16 22L12 20L8 22L4 20V5Z");
}

</style>
