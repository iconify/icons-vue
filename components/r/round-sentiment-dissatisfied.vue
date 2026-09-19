<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="mmn7xsb7v"/><circle class="an0_1xo_x"/><path class="rf7omh2gs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-sentiment-dissatisfied" /></template>
<style>
.an0_1xo_x {
  cx: 8.5px;
  cy: 9.5px;
  r: 1.5px;
  fill: currentColor;
}

.mmn7xsb7v {
  cx: 15.5px;
  cy: 9.5px;
  r: 1.5px;
  fill: currentColor;
}

.rf7omh2gs {
  fill: currentColor;
  d: path("M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2M12 20c-4.42 0-8-3.58-8-8s3.58-8 8-8s8 3.58 8 8s-3.58 8-8 8m0-6c-1.9 0-3.63.97-4.65 2.58a.747.747 0 1 0 1.27.79c.74-1.18 2-1.88 3.38-1.88s2.64.7 3.38 1.88c.14.23.39.35.64.35c.14 0 .27-.04.4-.11c.35-.22.46-.68.24-1.03C15.63 14.96 13.9 14 12 14");
}

</style>
