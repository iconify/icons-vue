<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="hatqhhbhq"/><path class="ls9phbj-f"/><path class="eko8djbrk"/><circle class="dowo_svno"/><circle class="o86a0b2jd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:thebattlecats" /></template>
<style>
.dowo_svno {
  cx: 17.617px;
  cy: 21.891px;
  r: 0.75px;
  fill: currentColor;
}

.eko8djbrk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.996 28.564c-.001 1.765 1.929 3.196 4.31 3.195s4.307-1.431 4.305-3.195q0-.101-.007-.202M20.25 32.371c-.001 4.07 3.07 7.368 3.752 7.368c.56-.001 3.749-3.3 3.748-7.368q0-.233-.007-.466");
}

.hatqhhbhq {
  cx: 24px;
  cy: 27.021px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 18.139px;
  ry: 15.479px;
}

.ls9phbj-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.236 5.5l1.067 4.882l.805 3.673a19.6 19.6 0 0 1 3.853-1.59L15.41 9.36Zm23.528 0L32.59 9.36l-2.528 3.077a19.6 19.6 0 0 1 3.832 1.613l.803-3.668ZM21.28 25.828c0 1.114 1.218 2.018 2.72 2.017s2.72-.903 2.719-2.017q0-.063-.005-.127m-11.325 2.863c-.001 1.765 1.929 3.196 4.31 3.195c2.378 0 4.306-1.431 4.305-3.195q0-.101-.008-.202");
}

.o86a0b2jd {
  cx: 30.383px;
  cy: 21.891px;
  r: 0.75px;
  fill: currentColor;
}

</style>
