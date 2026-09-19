<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d_-w3fb5b"/><path class="vjpaevbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:upscaler" /></template>
<style>
.d_-w3fb5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24A21.5 21.5 0 1 1 24 2.5A21.5 21.5 0 0 1 45.5 24");
}

.vjpaevbxd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.356 24H24v13.644H10.356ZM2.5 24H24m0-21.5v43");
}

</style>
