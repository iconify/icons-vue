<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="c-7k8ny6z"/><circle class="spn--gbqm"/><circle class="je1366bsl"/><path class="xcyqucclz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:skull" /></template>
<style>
.c-7k8ny6z {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M34 16C34 6 26.837 0 18 0S2 6 2 16c0 5.574.002 10.388 6 12.64V33a3 3 0 1 0 6 0v-3.155q.487.04 1 .07V33a3 3 0 1 0 6 0v-3.085q.513-.03 1-.07V33a3 3 0 0 0 6 0v-4.36c5.998-2.252 6-7.066 6-12.64");
}

.je1366bsl {
  cx: 25px;
  cy: 14px;
  r: 5px;
  fill: var(--svg-color--292f33, #292f33);
}

.spn--gbqm {
  cx: 11px;
  cy: 14px;
  r: 5px;
  fill: var(--svg-color--292f33, #292f33);
}

.xcyqucclz {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M19.903 23.062C19.651 22.449 18.9 22 18 22s-1.652.449-1.903 1.062A1.494 1.494 0 0 0 15 24.5a1.5 1.5 0 0 0 1.5 1.5c.655 0 1.206-.422 1.41-1.007c.03.001.059.007.09.007s.06-.006.09-.007a1.496 1.496 0 1 0 1.813-1.931");
}

</style>
