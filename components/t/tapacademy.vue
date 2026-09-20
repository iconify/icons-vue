<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dhfjxbb8k"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tapacademy" /></template>
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

.dhfjxbb8k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.464 22.987v-6.032h1.974c1.117 0 2.022.907 2.022 2.026s-.905 2.025-2.022 2.025h-1.975M5.5 16.955h3.996m-1.998 6.032v-6.032m2.905 6.014l1.959-6.014m1.961 6.032l-1.961-6.032m1.305 4.014h-2.613m15.599 10.076h4.917m-4.917-6.032h3.016m-3.016 3.016h1.967m2.95 1.508v-4.524l3.016 6.032l3.016-6.023v6.023M24.9 27.652v.754a2.64 2.64 0 0 1-2.64 2.64h-1.357v-6.033H24.9m18.698 0L41.6 28.029l-1.998-3.016m1.998 6.032v-3.016m-27.241.993v.025a1.998 1.998 0 0 1-3.996 0v-2.036a1.998 1.998 0 0 1 3.996 0v.025M5.5 31.027l1.959-6.014m1.962 6.032l-1.962-6.032m1.306 4.014H6.152m9.169 2l1.959-6.014m1.962 6.032l-1.962-6.032m1.306 4.014h-2.614");
}

</style>
