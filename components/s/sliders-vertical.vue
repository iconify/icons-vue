<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9kgs3l3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sliders-vertical" /></template>
<style>
.k9kgs3l3x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 3L5 12M5 21L5 16M3 16L7 16M12 3L12 10M12 21L12 14M10 10L14 10M19 3L19 10M19 21L19 14M17 14L21 14");
}

</style>
