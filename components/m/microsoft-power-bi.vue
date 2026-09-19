<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tev90cc-i"/><path class="t21ozyb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microsoft-power-bi" /></template>
<style>
.t21ozyb5t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.169 23.613v-7.44a2 2 0 0 1 2-2h9.508a2 2 0 0 1 2 2v27.476h-8.79");
}

.tev90cc-i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.379 23.613h9.508a2 2 0 0 1 2 2v18.036H11.379a2 2 0 0 1-2-2V25.613a2 2 0 0 1 2-2m15.58-9.44V6.649a2 2 0 0 1 2-2h9.508a2 2 0 0 1 2 2v35a2 2 0 0 1-2 2h-6.79");
}

</style>
