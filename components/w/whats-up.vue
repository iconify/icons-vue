<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="luxoa1i-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:whats-up" /></template>
<style>
.luxoa1i-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.5 5.77l-7.251 11.29l-25.548.02L5.5 42.23l6.802-10.783l25.716-.072Z");
}

</style>
