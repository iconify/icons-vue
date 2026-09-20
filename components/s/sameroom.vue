<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<rect class="v1vhne0np"/><path class="rz0m48jba"/><path class="o1d480o-z"/><path class="vhu6_3gmw"/><path class="pfdou9b4c"/><path class="z74o-i4bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:sameroom" /></template>
<style>
.o1d480o-z {
  fill: var(--svg-color--1b94b8, #1b94b8);
  d: path("M65.57 114.495c0 10.617-8.607 19.223-19.224 19.223s-19.223-8.606-19.223-19.223s8.606-19.224 19.223-19.224s19.224 8.607 19.224 19.224");
}

.pfdou9b4c {
  fill: var(--svg-color--1b94b8, #1b94b8);
  d: path("M230.301 114.495c0 10.617-8.607 19.223-19.224 19.223s-19.224-8.606-19.224-19.223s8.607-19.224 19.224-19.224s19.224 8.607 19.224 19.224");
}

.rz0m48jba {
  fill: var(--svg-color--fff, #fff);
  d: path("M80.437 114.495c0 18.828-15.263 34.09-34.091 34.09s-34.09-15.262-34.09-34.09s15.262-34.09 34.09-34.09s34.091 15.262 34.091 34.09");
}

.v1vhne0np {
  width: 256px;
  height: 256px;
  fill: var(--svg-color--78787a, #78787a);
  rx: 14px;
}

.vhu6_3gmw {
  fill: var(--svg-color--fff, #fff);
  d: path("M245.168 114.495c0 18.828-15.264 34.09-34.092 34.09s-34.09-15.262-34.09-34.09s15.262-34.09 34.09-34.09s34.092 15.262 34.092 34.09");
}

.z74o-i4bv {
  d: path("M127.903 209.484c-17.907 0-38.038-5.336-58.089-21.416a8.66 8.66 0 0 1 10.833-13.514c48.448 38.867 96.529 2.085 98.55.495c3.763-2.948 9.2-2.296 12.156 1.45c2.951 3.751 2.326 9.175-1.416 12.14c-.398.317-26.926 20.845-62.034 20.845");
}

</style>
