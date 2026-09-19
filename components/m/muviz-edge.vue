<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ofvutzbjk"/><path class="k_3sr2hrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:muviz-edge" /></template>
<style>
.k_3sr2hrx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.557 16.032L22.638 5.696L12.079 42.5l9.041-5.735m5.407-3.43l15.154-9.613l-5.398-5.109");
}

.ofvutzbjk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.362 15.424L16.879 5.5L6.319 42.304l29.602-18.778l-5.062-4.791");
}

</style>
