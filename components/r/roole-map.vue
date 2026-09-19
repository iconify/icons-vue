<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="faz-3_zwy"/><path class="g_2fopbrj"/><path class="wpf74geqc"/><path class="zmr5o9bzv"/><path class="ptstqk4jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:roole-map" /></template>
<style>
.faz-3_zwy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.58 42.5V24.47c0-8.25 6.7-14.94 14.94-14.94h8.98");
}

.g_2fopbrj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.34 42.5V25.02c0-4.82 3.92-8.73 8.74-8.73h8.42");
}

.ptstqk4jf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 9.5v29c0 2.208-1.792 4-4 4h-29c-2.208 0-4-1.792-4-4v-29c0-2.208 1.792-4 4-4h29c2.208 0 4 1.792 4 4");
}

.wpf74geqc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.67 42.5V25.11c0-6.44 5.23-11.67 11.67-11.67h8.16");
}

.zmr5o9bzv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.51 42.5V25.61c0-2.83 2.3-5.13 5.14-5.13h7.85");
}

</style>
