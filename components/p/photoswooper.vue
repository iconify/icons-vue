<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oq9sw2b-h"/><path class="byxb4abdj"/><circle class="yid5soboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:photoswooper" /></template>
<style>
.byxb4abdj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.683 16.344h-2.48a2 2 0 0 0-2 2v15.798a2 2 0 0 0 2 2H32a2 2 0 0 0 2-2v-2.508");
}

.oq9sw2b-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.498 21.507h3.122m-3.122-6h3.122m-3.122 12h3.122m25.882-1.877V13.857a2 2 0 0 0-2-2H20.704a2 2 0 0 0-2 2v15.798a2 2 0 0 0 2 2h.573m17.225-6.027v4.027a2 2 0 0 1-2 2H21.277m17.225-6.027l-4.414-4.008a2 2 0 0 0-2.753.06l-10.058 9.975");
}

.yid5soboi {
  cx: 25.882px;
  cy: 18.507px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
}

</style>
