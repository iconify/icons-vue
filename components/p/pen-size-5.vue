<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au-_4ge1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pen-size-5" /></template>
<style>
.au-_4ge1w {
  fill: currentColor;
  d: path("M5 16q0-1.25.875-2.125l8-8Q14.75 5 16 5t2.125.875T19 8t-.875 2.125l-8 8Q9.25 19 8 19t-2.125-.875T5 16");
}

</style>
