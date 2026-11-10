<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qeek1-4oa"/><circle class="fpf83zbwx"/><path class="ngnbow9ws"/><circle class="d_kuu5bsm"/><circle class="v-ofq7b7p"/><path class="wzn7v5b0h"/><path class="kw34-xxib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:skymap-alt" /></template>
<style>
.d_kuu5bsm {
  cx: 11.673px;
  cy: 32.816px;
  r: 2.096px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fpf83zbwx {
  cx: 24.047px;
  cy: 23.935px;
  r: 9.779px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kw34-xxib {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.612 13.258c-1.397.399-2.794.798-4.191 1.097m-3.493.699c-1.197.2-2.295.3-3.492.499m-10.678 0a53 53 0 0 1-11.575-2.395m33.629 21.155a61.7 61.7 0 0 0-11.177-2.295m-11.376-.1c-1.496.1-3.093.4-4.59.599m-4.091.998a19 19 0 0 0-2.195.698m32.231-10.577h-5.788m-19.758 0H8.38");
}

.ngnbow9ws {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.75 16.65l1.796 3.593l3.992.599l-2.894 2.794l.698 3.891l-3.492-1.896l-3.493 1.896l.699-3.891l-2.894-2.794l3.991-.6zM11.574 7.07l.299 1.597l1.497.699l-1.397.798l-.2 1.696l-1.197-1.097l-1.597.399l.699-1.497l-.899-1.497l1.697.2z");
}

.qeek1-4oa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.413 5.574a47.05 47.05 0 0 1-32.83 0c-.999-.4-2.296.898-1.997 1.996c3.194 10.777 3.693 21.654 0 32.83c-.3.998.998 2.395 1.996 1.996c10.578-4.59 21.355-5.489 32.83 0c.998.499 2.296-.898 1.996-1.996c-2.395-9.58-4.29-19.16 0-32.83a1.647 1.647 0 0 0-1.995-1.996M31.132 31.02l8.083 8.083M23.748 8.867v5.189m0 19.858v4.39");
}

.v-ofq7b7p {
  cx: 34.824px;
  cy: 15.154px;
  r: 1.796px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wzn7v5b0h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.57 7.57a69 69 0 0 1 2.294 10.777m.1 11.176a49.3 49.3 0 0 1-2.295 10.478M34.525 7.57a59.4 59.4 0 0 0-2.295 10.777m-.2 11.376A53 53 0 0 0 34.226 39.9");
}

</style>
