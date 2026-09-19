<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(45 24 24)" class="rn8wb3gft"/><path class="sracxv9ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:proton-pass" /></template>
<style>
.rn8wb3gft {
  width: 31.242px;
  height: 31.242px;
  x: 8.379px;
  y: 8.379px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.sracxv9ue {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.624 39.716L4.736 26.828a4 4 0 0 1 0-5.657L17.624 8.283a3 3 0 0 1 4.243 0l13.595 13.595a3 3 0 0 1 0 4.243L21.867 39.716a3 3 0 0 1-4.243 0");
}

</style>
