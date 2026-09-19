<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wxwg-ubkt"/><path class="wspv4fb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-supplies" /></template>
<style>
.wspv4fb1t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24A21.5 21.5 0 0 1 24 45.5A21.5 21.5 0 0 1 2.5 24A21.5 21.5 0 0 1 24 2.5A21.5 21.5 0 0 1 45.5 24");
}

.wxwg-ubkt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.047 24.364l6.57 6.454L33.6 16.94");
}

</style>
