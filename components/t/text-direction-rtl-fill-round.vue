<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1s5r38_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-direction-rtl-fill-round" /></template>
<style>
.e1s5r38_x {
  fill: currentColor;
  d: path("M11 2h6a1 1 0 0 1 0 2v7a1 1 0 0 1-2 0V4h-2v7a1 1 0 0 1-2 0v-1a4 4 0 0 1 0-8m0 2a2 2 0 1 0 0 4ZM6.707 15.707L5.414 17H21a1 1 0 0 1 0 2H5.414l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414");
}

</style>
