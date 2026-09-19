<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sy0vwcb7p"/><path class="o24wtvv3h"/><path class="jrx-udbpx"/><path class="bhn_-e0xt"/><path class="b_qx9hvyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mobywatel" /></template>
<style>
.b_qx9hvyp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M24 10.36V8.202m-1.643 2.149l-1.08-1.87m4.366 1.87l1.08-1.87");
}

.bhn_-e0xt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.027 12.878a6.803 6.803 0 0 1 6.801 6.802m-5.304-4.233h-4.405m4.693 2.416h-4.405m4.844 2.417h-4.405m6.079 2.416H13.52m5.88 1.119l-3.115 3.114m5.655-2.096l-3.114 3.115m3.312-.018l-3.965 3.964m-1.419 1.419l-1.324 1.324m3.187-1.001l1.023 1.022m-3.521-2.723h-1.446m8.64-1.811l-1.2 1.2m1.2 1l-1.2 1.2m1.2 1l-1.2 1.2");
}

.jrx-udbpx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.432 12.878a6.803 6.803 0 0 0-6.802 6.802m5.305-4.233h4.404m-4.693 2.416h4.405m-4.844 2.417h4.405m-6.079 2.416h4.405m-5.88 1.119l3.115 3.114m-5.655-2.096l3.115 3.115m-3.313-.018l3.965 3.964m1.42 1.419l1.323 1.324m-3.188-1.001l-1.021 1.022m3.521-2.723h1.446m-8.64-1.811l1.2 1.2m-1.2 1l1.2 1.2m-1.2 1l1.2 1.2M24.23 23.08a6.803 6.803 0 0 1-6.803-6.8");
}

.o24wtvv3h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.23 28.204v-12.6h0a3.586 3.586 0 0 0-3.587-3.56M24.23 23.08a6.803 6.803 0 0 0 6.8-6.8");
}

.sy0vwcb7p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.47c1.69 0 15.25-7.77 15.25-16.94v-20c-4 0-15.25-2-15.25-2s-11.26 2-15.25 2v20c0 9.17 13.56 16.94 15.25 16.94");
}

</style>
