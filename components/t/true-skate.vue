<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d-eezobvb"/><rect transform="rotate(-45 10.954 28.121)" class="pa695rb-c"/><rect transform="rotate(-45 19.879 37.046)" class="u14ta0elm"/><path class="ttngc4byj"/><rect transform="rotate(-45 28.121 10.954)" class="bdhfmwjxu"/><rect transform="rotate(-45 37.046 19.879)" class="pwcxu0b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:true-skate" /></template>
<style>
.bdhfmwjxu {
  width: 5.084px;
  height: 3.944px;
  x: 25.58px;
  y: 8.982px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.008px;
  ry: 1.008px;
}

.d-eezobvb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.615 22.659L22.659 36.615m2.682-25.23L11.385 25.341M28.554 8.173l.346-.346c3.102-3.102 8.171-3.102 11.273 0a7.92 7.92 0 0 1 2.321 5.636a7.92 7.92 0 0 1-2.32 5.637l-.347.346M19.446 39.827l-.346.346c-3.102 3.102-8.171 3.102-11.273 0a7.92 7.92 0 0 1-2.321-5.636a7.92 7.92 0 0 1 2.32-5.637l.347-.346m10.311 7.098l-6.136-6.136m.682 3.533l2.85-2.851l1.922 1.92l-2.851 2.852z");
}

.pa695rb-c {
  width: 5.084px;
  height: 3.944px;
  x: 8.412px;
  y: 26.149px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.008px;
  ry: 1.008px;
}

.pwcxu0b6c {
  width: 5.084px;
  height: 3.944px;
  x: 34.504px;
  y: 17.907px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.008px;
  ry: 1.008px;
}

.ttngc4byj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.652 18.484l-6.136-6.136m.682 3.533l2.851-2.85l1.921 1.92l-2.85 2.851z");
}

.u14ta0elm {
  width: 5.084px;
  height: 3.944px;
  x: 17.337px;
  y: 35.074px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.008px;
  ry: 1.008px;
}

</style>
