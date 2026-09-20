<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="uzdg-yyew"/><path class="rddqhvb9r"/><path class="m3hm_xbpp"/><path class="ljbqgmbfg"/><path class="vn842wbpk"/><path class="oichxqvpg"/><path class="wo_q4rklv"/><circle class="zlewv7pjp"/><circle class="rhoz-mbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:squid" /></template>
<style>
.ljbqgmbfg {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M13 15.867c2.552 4.254-1.806 9.096-4.357 8.245s-3.403 1.701-.851 2.552s8.052-.396 11.059-3.402c.851-.851 1.701-.851 1.701-.851z");
}

.m3hm_xbpp {
  fill: var(--svg-color--f4abba, #f4abba);
  d: path("M27 11c0 3.833-9 12-9 12s-9-8.167-9-12c0-5 9-11 9-11s9 6 9 11");
}

.oichxqvpg {
  fill: var(--svg-color--ea596e, #ea596e);
  d: path("M9 17c2.552 4.254-1.369 11.366-3.921 10.515s-3.403 1.702-.851 2.553s8.052-.396 11.059-3.403c.851-.851 1.701-.851 1.701-.851zm17.989 0c-2.553 4.254 1.368 11.366 3.921 10.515s3.402 1.702.851 2.553c-2.553.851-8.052-.396-11.059-3.403c-.851-.852-1.702-.852-1.702-.852z");
}

.rddqhvb9r {
  fill: var(--svg-color--ea596e, #ea596e);
  d: path("M5.002 11c0-6 13-11 13-11v25c.001 0-13-8-13-14");
}

.rhoz-mbxt {
  cx: 21.5px;
  cy: 23.5px;
  r: 2.5px;
  fill: var(--svg-color--292f33, #292f33);
}

.uzdg-yyew {
  fill: var(--svg-color--ea596e, #ea596e);
  d: path("M31 11C31 5 18 0 18 0v25s13-8 13-14");
}

.vn842wbpk {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M23 15.867c-2.552 4.254 1.806 9.096 4.357 8.245c2.553-.851 3.403 1.701.851 2.552s-8.052-.396-11.059-3.402c-.851-.851-1.702-.851-1.702-.851z");
}

.wo_q4rklv {
  fill: var(--svg-color--f4abba, #f4abba);
  d: path("M30.921 32.35C28.599 33.124 24 27 25 21c2-5-4-7.482-4-9.983c0-6.108-2.031-9.735-3.031-9.735S15 4.909 15 11.017C15 13.518 9 16 11 21c1 6-3.599 12.124-5.921 11.35c-2.552-.851-3.403 2.552-.851 3.402s7.069-.533 10.208-3.402C16.299 30.647 18 30.647 18 30.647s1.701 0 3.563 1.702c3.139 2.869 7.656 4.253 10.208 3.402c2.552-.85 1.702-4.252-.85-3.401");
}

.zlewv7pjp {
  cx: 14.5px;
  cy: 23.5px;
  r: 2.5px;
  fill: var(--svg-color--292f33, #292f33);
}

</style>
