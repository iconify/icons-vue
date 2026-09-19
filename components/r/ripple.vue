<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o5m802bqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ripple" /></template>
<style>
.o5m802bqa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5A14.27 14.27 0 0 1 9.75 29.32C9.75 19.89 24 4.5 24 4.5s14.25 15.39 14.25 24.82A14.27 14.27 0 0 1 24 43.5");
}

</style>
