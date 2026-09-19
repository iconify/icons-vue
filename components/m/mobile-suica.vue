<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k3xizubfq"/><path class="r8gbbnbwi"/><circle class="uwz0hsfux"/><circle class="wac730bjo"/><ellipse transform="rotate(-4.031 19.387 25.672)" class="v3g3wbb2n"/><path class="zh7i2sb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mobile-suica" /></template>
<style>
.k3xizubfq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.547 32.772v-6.46h-5.035v8.147h3.535");
}

.r8gbbnbwi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.995 32.313a14.77 14.77 0 0 1-18.714 4.019a14.77 14.77 0 0 1-6.973-17.826a14.773 14.773 0 0 1 28.74 4.95");
}

.uwz0hsfux {
  cx: 10.678px;
  cy: 23.552px;
  r: 2.319px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v3g3wbb2n {
  cx: 19.387px;
  cy: 25.671px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.426px;
  ry: 3.091px;
}

.wac730bjo {
  cx: 27.461px;
  cy: 21.856px;
  r: 2.319px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zh7i2sb8t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.743 25.882c1.068.792 4.956.31 5.5-.399m8.803-2.002h8.002v9.469c-2.486-.625-3.53.533-2.89 1.702c.512.933 1.475 1.01 2.796 2.652h-7.908zm8.002 9.469c2.254.608 3.91 2.288 4.35 3.882c.525 1.906-1.112 2.707-1.823 2.616c-1.918-.245-1.795-1.167-2.62-2.144m-1.408-8.083l-5.035 2.54");
}

</style>
