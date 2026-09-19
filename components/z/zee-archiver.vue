<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rw3hv_efr"/><path class="gh-9ft5lp"/><path class="u7_dsubni"/><path class="fjjn9qcky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zee-archiver" /></template>
<style>
.fjjn9qcky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.628 15.766c-.02 0-1.374-1.316-1.374-1.316l2.07-.755l1.22 1.155zm1.058-1.891s3.555-2.628 4.915-1.312s-4.281 2.032-4.281 2.032");
}

.gh-9ft5lp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.326 12.931L28.412 5.5l13.262 8.721l-1.496 16.358L20.723 42.5m0-18.474l20.951-9.805");
}

.rw3hv_efr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.723 42.5L8.648 31.457L6.326 12.931l14.397 11.095z");
}

.u7_dsubni {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.326 12.931c2.528 1.239 8.042 3.388 12.687 2.253c-3.406 2.683.636 7.603 1.71 8.842m5.051-11.579l8.498-3.093");
}

</style>
