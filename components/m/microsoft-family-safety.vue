<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="knyt3iiyf"/><path class="a3_diccep"/><path class="u11cz32gv"/><path class="otfs-ybfh"/><path class="srh2arb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microsoft-family-safety" /></template>
<style>
.a3_diccep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.857 5.036c7.535 0 13.643 6.108 13.643 13.643a13.62 13.62 0 0 1-5.293 10.79v.001a7.612 7.612 0 0 0-5.94-12.373h-3.236a6.03 6.03 0 0 1 0-12.061z");
}

.knyt3iiyf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.143 5.036C9.608 5.036 3.5 11.144 3.5 18.679a13.62 13.62 0 0 0 5.293 10.79v.001a7.612 7.612 0 0 1 5.94-12.373h3.236a6.03 6.03 0 0 0 0-12.061z");
}

.otfs-ybfh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.566 31.243c3.79 3.791 9.937 3.791 13.728 0l5.438-5.438a9.92 9.92 0 0 0 2.904-7.013v-1.695");
}

.srh2arb5o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.49 31.047l-5.242-5.242a9.92 9.92 0 0 1-2.905-7.013v-1.695");
}

.u11cz32gv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.793 29.47l12.285 12.284a4.13 4.13 0 0 0 5.844 0l12.285-12.285");
}

</style>
