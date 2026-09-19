<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ofu66bc2h"/><path class="ml64twbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:supersports" /></template>
<style>
.ml64twbpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.058 32.39c-3.694-7.015.195-12.358 6.549-15.343C34.072 11.659 47.644 9.18 42.3 8.748C21.326 7.056-13.69 19.746 16.058 32.39");
}

.ofu66bc2h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.942 15.61c3.694 7.015-.195 12.358-6.549 15.344C13.928 36.34.356 38.82 5.7 39.252c20.974 1.692 55.99-10.998 26.242-23.641");
}

</style>
