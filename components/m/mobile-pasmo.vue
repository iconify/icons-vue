<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j-qbe_k1d"/><ellipse class="xl6qttbcp"/><ellipse class="tckrcbc-k"/><ellipse class="e0d73y90j"/><ellipse class="fgzbj78eh"/><path class="mkwad_bha"/><path class="i1qax9f9g"/><path class="qfr8njibc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mobile-pasmo" /></template>
<style>
.e0d73y90j {
  cx: 27.166px;
  cy: 24.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.342px;
  ry: 3.272px;
}

.fgzbj78eh {
  cx: 28.151px;
  cy: 24.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.358px;
  ry: 2.442px;
}

.i1qax9f9g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.745 28.473h8.576v12.498h-8.576z");
}

.j-qbe_k1d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.306 37.095a3.194 3.194 0 1 1-3.105 3.942m-20.006-6.554h7.426");
}

.mkwad_bha {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.519 7.504a1.6 1.6 0 1 1 1.6 0m.924 6.554l-.924-6.554m-2.706 6.554l1.106-6.554m12.22 30.789l-23.096-.045c-2.849-.006-4.839-2.227-4.891-5.075L4.5 19.603c-.053-2.843 2.409-5.136 5.142-5.143c4-.184 6.707-.36 9.77-.402m3.63 0c4.367-.016 7.062.165 9.128.402c2.83.325 4.962 2.3 5.142 5.142c.14 2.234-.221 5.513-.221 8.88m-2.944 1.373h5.774v8.288h-5.774zm1.88 9.723h2.011m-2.462-8.168v2.763m2.916-2.763v2.763m-1.458-2.763v2.763");
}

.qfr8njibc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.333 28.48l-.013-9.783H8.493v12.425h24.235");
}

.tckrcbc-k {
  cx: 15.646px;
  cy: 24.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.358px;
  ry: 2.442px;
}

.xl6qttbcp {
  cx: 14.662px;
  cy: 24.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.342px;
  ry: 3.272px;
}

</style>
