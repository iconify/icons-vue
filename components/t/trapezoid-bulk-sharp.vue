<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf_a4abld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trapezoid-bulk-sharp" /></template>
<style>
.rf_a4abld {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m3.217 2.024l18 4A1 1 0 0 1 22 7v10a1 1 0 0 1-.783.976l-18 4A1 1 0 0 1 2 21V3a1.002 1.002 0 0 1 1.217-.976");
}

</style>
