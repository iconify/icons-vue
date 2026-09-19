<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l21-83fmt"/><path class="c2pkwye4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nagram" /></template>
<style>
.c2pkwye4d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.843 42.5a5.39 5.39 0 0 1-4.321-2.157L9.845 14.14a5.397 5.397 0 1 1 8.633-6.482L38.155 33.86a5.397 5.397 0 0 1-4.312 8.639");
}

.l21-83fmt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.44 20.923V10.898a5.399 5.399 0 0 1 10.796 0v26.204M19.56 27.077v10.025a5.399 5.399 0 0 1-10.796 0V10.898");
}

</style>
