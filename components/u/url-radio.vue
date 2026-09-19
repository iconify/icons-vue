<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tp2p6rbzy"/><ellipse class="oci3e_b5i"/><circle class="pwfav5ija"/><circle class="p6g73j0yb"/><circle class="k6zr320-f"/><path class="hn3lf-b4m"/><path class="kr_g5sbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:url-radio" /></template>
<style>
.hn3lf-b4m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.178 17.247h10.348a1.614 1.614 0 0 1 1.614 1.614v5.986a1.61 1.61 0 0 1-1.61 1.61H28.178a1.61 1.61 0 0 1-1.61-1.61v-5.99a1.61 1.61 0 0 1 1.61-1.61");
}

.k6zr320-f {
  cx: 38.723px;
  cy: 30.375px;
  r: 1.417px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kr_g5sbww {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.54 20.187v3.331h1.669m-5.836 0v-3.331h1.085a1.124 1.124 0 1 1 0 2.248h-1.085m1.127-.041l1.085 1.124m-6.087-3.332v2.207a1.086 1.086 0 1 0 2.17 0v-2.207");
}

.oci3e_b5i {
  cx: 15.278px;
  cy: 23.787px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.355px;
  ry: 7.339px;
}

.p6g73j0yb {
  cx: 33.349px;
  cy: 30.376px;
  r: 1.417px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pwfav5ija {
  cx: 27.985px;
  cy: 30.376px;
  r: 1.417px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tp2p6rbzy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.006 11.676H41.99a1.51 1.51 0 0 1 1.509 1.508V34.82a1.506 1.506 0 0 1-1.505 1.505H6.009A1.51 1.51 0 0 1 4.5 34.816V13.18a1.506 1.506 0 0 1 1.505-1.505");
}

</style>
