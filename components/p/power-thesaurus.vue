<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z_cuasbxt"/><circle class="xkz8djbdu"/><path class="lrie4k-4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:power-thesaurus" /></template>
<style>
.lrie4k-4i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.682 38.986V43.5H8.5v-39h10.182v3.545H24v10.636h-5.318V24");
}

.xkz8djbdu {
  cx: 24px;
  cy: 24px;
  r: 5.318px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z_cuasbxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 4.5v3.545m0 3.546v3.545m0 3.546v3.545m0 3.546v3.545m0 3.546v3.545m0 3.546V43.5M24 8.045c6.27 0 11.92 3.887 14.32 9.85c2.399 5.961 1.073 12.823-3.36 17.386s-11.1 5.928-16.892 3.459C12.276 36.27 8.5 30.453 8.5 24");
}

</style>
