<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="oq0d4tbkn"/><g class="ed4r-5bxj"><circle class="b570g9hbj"/><path class="di_19vd7c"/><circle class="f3fv_lbyr"/><circle class="cbx1tkb0p"/><circle class="xj_loue8u"/><path class="une2ler2d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:new-moon" /></template>
<style>
.b570g9hbj {
  cx: 29.31px;
  cy: 52.982px;
  r: 9.262px;
}

.cbx1tkb0p {
  cx: 6.211px;
  cy: 18.742px;
  r: 2.204px;
}

.di_19vd7c {
  d: path("M41.943 24.333a3.936 3.936 0 0 1-7.869 0a3.934 3.934 0 0 1 7.869 0");
}

.ed4r-5bxj {
  fill: var(--svg-color--4f6977, #4f6977);
}

.f3fv_lbyr {
  cx: 5.863px;
  cy: 36.434px;
  r: 3.86px;
}

.oq0d4tbkn {
  cx: 32px;
  cy: 32px;
  r: 32px;
  fill: var(--svg-color--405866, #405866);
}

.une2ler2d {
  d: path("M47.792 10.867a4.853 4.853 0 1 1-9.706 0a4.853 4.853 0 0 1 9.706 0");
}

.xj_loue8u {
  cx: 17.477px;
  cy: 19.481px;
  r: 3.446px;
}

</style>
