<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myjix-b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sort-a-z-duocolor-sharp" /></template>
<style>
.myjix-b9t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 17l3 3l3-3m-3 3V4m7 6V7a3 3 0 0 1 6 0v3m-6-2h6m-6 6h6l-6 6h6");
}

</style>
