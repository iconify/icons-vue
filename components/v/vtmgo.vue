<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="juh6-0b-v"/><path class="j-dlzibql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vtmgo" /></template>
<style>
.j-dlzibql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.389 40.195S9.32 21.635 5.5 11.565l10.797-1.394c5.095 13.04 8.07 19.533 8.07 19.533");
}

.juh6-0b-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.157 8.897c-1.213 16.377-13.769 31.298-13.769 31.298H29.52C41.772 24 42.5 7.805 42.5 7.805z");
}

</style>
