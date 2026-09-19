<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ip-59rbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:transport-gzm" /></template>
<style>
.ip-59rbek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.214 12.536L4.5 29.733v5.732h11.143l22.286-22.93H43.5v22.93H26.786v-22.93z");
}

</style>
