<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fmpio0g-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:starling" /></template>
<style>
.fmpio0g-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.25 24v-1.5a18 18 0 0 1 18-18h1.5m0 19.5v1.5a18 18 0 0 1-18 18h-1.5");
}

</style>
