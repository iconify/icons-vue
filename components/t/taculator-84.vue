<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zpzkeob-v"/><circle class="ifxlxf06v"/><path class="q-ntb3blv"/><path class="nu0up3x4z"/><rect class="hu_6b4bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:taculator-84" /></template>
<style>
.hu_6b4bnf {
  width: 34.895px;
  height: 39px;
  x: 6.553px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.ifxlxf06v {
  cx: 34.466px;
  cy: 36.628px;
  r: 3.372px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nu0up3x4z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.259 8c.475 0 .86.386.86.862v17.765a.86.86 0 0 1-.86.861H10.723a.86.86 0 0 1-.86-.862V8.887c0-.49.396-.886.885-.886z");
}

.q-ntb3blv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.862 33.257h2.436v1.949H9.862zm0 4.794h2.436V40H9.862zm0-14.461s3.329-9.744 7.308-9.744s6.82 3.898 6.82 3.898s5.096 7.208 8.77 2.923c3.675-4.284 5.36-8.77 5.36-8.77");
}

.zpzkeob-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.862 30.411h2.436m2.732 0h2.436m7.9 0h2.436m2.732 0h2.436m2.732 0h2.436m-17.94 0h2.436m11.832 3.333v.487m-2.903 2.416h.487m2.416 2.415v.487m2.415-2.902h.487");
}

</style>
