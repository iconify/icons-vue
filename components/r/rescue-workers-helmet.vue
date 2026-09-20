<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ys-3xnb4a"/><path class="wrlqcbcec"/><path class="ps-8g7bod"/><path class="iymry9b5q"/><path class="iwjzollwd"/><path class="z0oendmmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:rescue-workers-helmet" /></template>
<style>
.iwjzollwd {
  fill: var(--svg-color--a0041e, #a0041e);
  d: path("M25 19a1 1 0 0 1-1-1c0-7.728-1.93-13.625-1.949-13.684a1 1 0 0 1 1.898-.633c.08.24 1.876 5.71 2.04 13.223c1.139-.161 3.165-.602 5.564-1.801a1 1 0 0 1 .895 1.789C28.284 18.976 25.132 19 25 19m-14 0c-.132 0-3.284-.024-7.447-2.106a1 1 0 0 1 .895-1.789c2.399 1.2 4.425 1.64 5.565 1.801c.164-7.513 1.959-12.983 2.039-13.223a1 1 0 0 1 1.897.633C13.929 4.374 12 10.271 12 18a1 1 0 0 1-1 1");
}

.iymry9b5q {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M3 16C3 9 9.198 2 18 2s15 7 15 14c0 1-6.198 4-15 4S3 17 3 16");
}

.ps-8g7bod {
  fill: var(--svg-color--ea596e, #ea596e);
  d: path("M2 17c0-2.762 6.611-5 16-5s16 2.238 16 5s-6.611 6-16 6s-16-3.239-16-6");
}

.wrlqcbcec {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M22 32.083A1.917 1.917 0 0 1 20.083 34h-4.166A1.917 1.917 0 0 1 14 32.083v-.166c0-1.059.858-1.917 1.917-1.917h4.166c1.059 0 1.917.858 1.917 1.917z");
}

.ys-3xnb4a {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M29 17v5c0 4.142-4.896 9-11 9S7 26.142 7 22v-5H5v5c0 5.246 5.268 11 13 11s13-5.754 13-11v-5z");
}

.z0oendmmt {
  fill: var(--svg-color--fff, #fff);
  d: path("M21 12h-2v-2a1 1 0 0 0-2 0v2h-2a1 1 0 0 0 0 2h2v2a1 1 0 0 0 2 0v-2h2a1 1 0 1 0 0-2");
}

</style>
