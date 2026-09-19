<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="a2aobabww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:power-marathon" /></template>
<style>
.a2aobabww {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.916 41.178l22.037-2.468l-9.14-4.878l23.687-3.14M16.57 24.58c1.234-4.206 2.495-6.59 4.767-6.59c2.467 0 2.887 2.16 4.71 2.16s2.944-5.328 2.944-5.328M33 28.056c-4.906-1.29-10.822-4.906-10.822-4.906c-.645 2.663-1.374 7.542-4.823 7.542c-2.972 0-4.205-2.215-4.205-2.215m9.84-18.127a2.334 2.334 0 1 1-2.333 2.335V10.35z");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
