<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="juyvbccyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:naturalreader" /></template>
<style>
.juyvbccyl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 18v12m-4.5-18v12m9 0v12M6 42V6m4.5 36V6M15 42V6m18 36V6m9 36V6m-4.5 36V6");
}

</style>
