<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hmgozgbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:padland" /></template>
<style>
.hmgozgbuo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.75 42.5L5.5 30.366V5.5l9.25 12.134zm9.25 0l-9.25-12.134V5.5L24 17.634zm9.25 0L24 30.366V5.5l9.25 12.134zm9.25 0l-9.25-12.134V5.5l9.25 12.134z");
}

</style>
