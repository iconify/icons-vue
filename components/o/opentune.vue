<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vga-pvb-o"/><circle class="cpk0fnbgt"/><path class="di6ts5bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:opentune" /></template>
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

.di6ts5bkw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.81 22.147a14.87 14.87 0 0 0-9.966-12.312c-.407-.138-.984.015-.984.775v13.322m-.005.04a3.827 3.827 0 1 1-7.654 0a3.827 3.827 0 0 1 7.654 0");
}

.vga-pvb-o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.73 26.165c-1.047 7.195-7.242 12.72-14.728 12.72c-8.221 0-14.886-6.664-14.886-14.885S15.781 9.115 24.002 9.115");
}

</style>
