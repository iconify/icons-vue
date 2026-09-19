<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yjm1qhb_m"/><path class="ocbz32bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mgm-plus" /></template>
<style>
.ocbz32bkd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.6 22.004v4m-2-2h4m-15.07 3.99v-8l4 8l4-7.98v7.99m-10.41-5.35a2.65 2.65 0 1 0-5.3 0v2.7a2.65 2.65 0 0 0 5.3.003v-.003h-2.65M7.4 27.994v-8l4 8l4-7.98v7.99");
}

.yjm1qhb_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 35.5v-23a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v23a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4");
}

</style>
