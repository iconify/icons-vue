<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="fmk1h2biy"/><path class="q47mpdnwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:the-genesis-order" /></template>
<style>
.fmk1h2biy {
  cx: 26.804px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 18.696px;
  ry: 19.333px;
}

.q47mpdnwd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.39 6.331v35.342M2.5 25.885l4.907-1.883h1.18l.223.211h36.688m-11.11 17.461l.509 1.316");
}

</style>
