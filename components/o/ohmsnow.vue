<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zgkxo_eys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ohmsnow" /></template>
<style>
.zgkxo_eys {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 29l5.5 8.36h10.14C13.57 24.54 14.68 10.62 24 10.64s10.3 13.88 3.88 26.72H38L43.5 29");
}

</style>
