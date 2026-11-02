<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hko4sybov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-up-right-fill-sharp" /></template>
<style>
.hko4sybov {
  fill: currentColor;
  d: path("M2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m14-8V9a1 1 0 0 0-1-1h-4a1 1 0 0 0 0 2h1.586l-4.293 4.293a.999.999 0 1 0 1.414 1.414L14 11.414V13a1 1 0 0 0 2 0");
}

</style>
