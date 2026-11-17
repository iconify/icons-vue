<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqdhx-bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wind-turbine-solar-panel" /></template>
<style>
.qqdhx-bbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 7a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1 1v13m4 0l1-8h8l1 8ZM8.104 7.296l2.76.74c-.774.68-1.952.66-3.294-.05Zm-1.912.512l-2.02 2.02C3.97 8.818 4.576 7.808 5.86 7Zm.512-1.912l-.74-2.76c.977.33 1.548 1.36 1.606 2.877ZM16 13v8m-4.5-4h9");
}

</style>
