<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dzm3f5tqe"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:neoterm" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dzm3f5tqe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.204 30.247A4.47 4.47 0 0 0 16.127 32h2.369a3.996 3.996 0 0 0 3.99-4a3.996 3.996 0 0 0-3.99-4h-2.618a3.996 3.996 0 0 1-3.991-4a3.996 3.996 0 0 1 3.991-4h2.37a4.48 4.48 0 0 1 3.922 1.753M17.187 16v-2m0 20v-2m8.326 2h10.6");
}

</style>
