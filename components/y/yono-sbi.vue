<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hfjub6bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yono-sbi" /></template>
<style>
.hfjub6bdx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.22 46a22 22.02 0 1 0-2.44 0V27.65a3.67 3.67 0 1 1 2.44 0z");
}

</style>
