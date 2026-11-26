<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew82ccbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:zodiac-aquarius-sharp-fill" /></template>
<style>
.ew82ccbdc {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.7071 10.2929L6 6L10 10L14 6L18 10L22.2929 5.7071M1.7071 18.2929L6 14L10 18L14 14L18 18L22.2929 13.7071");
}

</style>
