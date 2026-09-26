<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n204dep_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sliders-horizontal-sharp-fill" /></template>
<style>
.n204dep_b {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 5L13 5M22 5L16 5M16 2L16 8M2 12L10 12M22 12L13 12M10 9L10 15M2 19L11 19M22 19L14 19M14 16L14 22");
}

</style>
