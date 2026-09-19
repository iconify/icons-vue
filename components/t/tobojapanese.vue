<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><circle class="xsz0obbxg"/><path class="pfb86e8hj"/><path class="b7b6h_b8n"/><circle class="b08sqgzbo"/><circle class="cafoh5b6r"/><rect class="j441xhbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tobojapanese" /></template>
<style>
.b08sqgzbo {
  cx: 28.335px;
  cy: 14.726px;
  r: 0.75px;
  fill: currentColor;
}

.b7b6h_b8n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.912 19.045c2.471 1.297 2.663 2.567 3.06 3.379m1.689-6.63c-.761 1.045-1.8 1.377-3.155.892");
}

.cafoh5b6r {
  cx: 23.968px;
  cy: 18.407px;
  r: 9.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.j441xhbcq {
  width: 8px;
  height: 8px;
  x: 20.039px;
  y: 31.543px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.pfb86e8hj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.258 26.991a9.25 9.25 0 1 1-.15-17.164m7.784-.032a9.25 9.25 0 1 1-.165 17.159m-7.886-8.403l4.239.032m-6.184 2.486l4.239.032m-3.92-4.781l4.239.032m-.526-1.801l4.239.032m-2.422 2.454c1.303-1.435 2.543-1.199 3.761-.35l-1.594 2.358s-1.57 2.148-3.474.797");
}

.xsz0obbxg {
  cx: 23.998px;
  cy: 35.502px;
  r: 1.316px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
