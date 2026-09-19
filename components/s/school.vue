<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="epn-sac_c"/><path class="l5wdow1lu"/><path class="qq8c7zg0b"/><circle class="bt22r8j_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:school" /></template>
<style>
.bt22r8j_f {
  cx: 39.416px;
  cy: 35.52px;
  r: 1.262px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.epn-sac_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 18.84L24 11.218L4.5 18.841L24 26.464z");
}

.l5wdow1lu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.397 21.538v6.101c0 1.961 5.642 3.554 12.603 3.554s12.604-1.593 12.604-3.554v-6.101");
}

.qq8c7zg0b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.87 18.84c5.395-.379 9.013-.071 10.978 1.82s.568 13.599.568 13.599");
}

</style>
