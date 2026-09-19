<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gzf8wrbzv"/><circle class="vyu-7l7wg"/><circle class="du0qzfw3z"/><path class="st7jvl76z"/><path class="am3lwq5zo"/><path class="qaqf37rsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:setedit" /></template>
<style>
.am3lwq5zo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.3 23.9a8.67 8.67 0 0 1-2.4 5.9a8.16 8.16 0 0 1-5.9 2.5");
}

.du0qzfw3z {
  cx: 15.9px;
  cy: 15.9px;
  r: 0.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gzf8wrbzv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.1 29.9l2.5-7.2L37.3 6a2 2 0 0 1 2.4 0l2.2 2.2a2 2 0 0 1-.1 2.6L25.1 27.5Zm2.5-7.1l4.5 4.8M22.9 25l6.6-6.5m5.3-9.9l4.7 4.5m-2.3-2.2l-3.7 3.5");
}

.qaqf37rsr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.5 10.8l-5-2l-.7-3.2h-5.6l-.8 3.2l-4.6 1.8l-3-1.6L9 12.9l1.7 2.9l-1.8 4.6l-3.4.8v5.7l3.2.8l2 4.5L8.9 35l4.1 4.1l2.7-1.7l4.7 1.8l.8 3.3h5.7l.9-3.5l4.3-1.6l3.1 1.7l3.9-3.9l-1.6-3l1.8-4.5l3.2-.9v-5.5l-3.6-1l-1.8-4.7m-17.5 9.8l2.8 3.1");
}

.st7jvl76z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.2 18.8a11.44 11.44 0 0 1-17.9 13.6A11.45 11.45 0 0 1 14.1 18m4-4a11.46 11.46 0 0 1 11.2-.3");
}

.vyu-7l7wg {
  cx: 31.5px;
  cy: 16.5px;
  r: 0.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
