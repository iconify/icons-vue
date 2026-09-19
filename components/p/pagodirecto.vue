<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="u1r89jbky"/><path class="osb08rrfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pagodirecto" /></template>
<style>
.osb08rrfe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.714 14.649V4.5l2.205 1.24l2.205-1.24V24m-19.838 9.351V43.5l-2.205-1.24l-2.205 1.24V24");
}

.u1r89jbky {
  cx: 24px;
  cy: 24px;
  r: 12.124px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
