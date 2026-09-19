<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bam-b320j"/><path class="nj-q2pfgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vrchat" /></template>
<style>
.bam-b320j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 10.364h-29a4 4 0 0 0-4 4v14a4 4 0 0 0 4 4h21.156l3.606 4.817c.651.87 2.034.409 2.034-.678v-4.139H38.5a4 4 0 0 0 4-4v-14a4 4 0 0 0-4-4");
}

.nj-q2pfgx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.403 26.663V16.066h3.47c1.96 0 3.55 1.593 3.55 3.559s-1.59 3.559-3.55 3.559h-3.47m3.469 0l3.47 3.476m-9.745-10.594l-3.51 10.597l-3.511-10.597");
}

</style>
