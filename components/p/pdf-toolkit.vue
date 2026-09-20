<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r4h1y5b9l"/><path class="pui0uw3-t"/><circle class="edzxdj8kw"/><circle class="v7sx0lbkg"/><path class="c6vj19b5k"/><path class="icagyabdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pdf-toolkit" /></template>
<style>
.c6vj19b5k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.07 27.544h1.964l3.858 2.413h3.858");
}

.edzxdj8kw {
  cx: 24.138px;
  cy: 28.444px;
  r: 7.885px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.icagyabdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.75 26.96h-3.893l-3.823 2.997H20.07m8.439-8.077l1.76-1.76a.555.555 0 0 1 .785 0l1.408 1.407a.555.555 0 0 1 0 .785l-1.76 1.76m0 8.743l1.76 1.76a.555.555 0 0 1 0 .786l-1.407 1.407a.555.555 0 0 1-.785 0l-1.76-1.76m-8.743.001l-1.76 1.76a.555.555 0 0 1-.786 0l-1.407-1.407a.555.555 0 0 1 0-.785l1.76-1.76m-.001-8.744l-1.76-1.76a.555.555 0 0 1 0-.785l1.407-1.408a.555.555 0 0 1 .785 0l1.76 1.76");
}

.pui0uw3-t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.587 20.712v-2.49c0-.307.248-.555.555-.555h1.99c.307 0 .555.249.555.555v2.49m6.183 6.181h2.49c.307 0 .555.249.555.555v1.99a.555.555 0 0 1-.555.556h-2.49m-6.181 6.183v2.49a.555.555 0 0 1-.555.555h-1.99a.555.555 0 0 1-.556-.555v-2.49m-6.183-6.182h-2.49a.555.555 0 0 1-.555-.555v-1.99c0-.307.249-.555.556-.555h2.489");
}

.r4h1y5b9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 15.5h-9a2 2 0 0 1-2-2v-9h-18a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h27a2 2 0 0 0 2-2zm-11-11l11 11");
}

.v7sx0lbkg {
  cx: 24.138px;
  cy: 28.445px;
  r: 4.356px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
