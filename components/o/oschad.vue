<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d2r3264na"/><path class="bi_gddbnb"/><path class="jkdcq-bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oschad" /></template>
<style>
.bi_gddbnb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.345 5.5C30.301 12.736 19.363 31.899 5.5 22.805");
}

.d2r3264na {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4Z");
}

.jkdcq-bah {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.1 5.5c7.904 18.65-9.691 34.218-26.6 28.502");
}

</style>
