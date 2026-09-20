<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l5wb0ubuc"/><path class="iye4g1_fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tellurium" /></template>
<style>
.iye4g1_fh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.65 31.103a4.75 4.75 0 0 1-8.877-2.353v-3.087a4.75 4.75 0 1 1 9.5 0v1.543H24.77");
}

.l5wb0ubuc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-24.772 9h12.588m-6.294 19v-19");
}

</style>
