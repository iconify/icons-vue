<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="vs4t_tlny"/><path clip-rule="evenodd" class="et5gqfwag"/><path class="f6y5q55up"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mft" /></template>
<style>
.et5gqfwag {
  fill: var(--svg-color--00a7e7, #00a7e7);
  fill-rule: evenodd;
  d: path("M21 12c0 2.982-2.357 5.4-5.265 5.4S10.47 14.982 10.47 12s2.357-5.4 5.265-5.4S21 9.017 21 12m-2.97 0c0 1.3-1.028 2.354-2.296 2.354S13.44 13.3 13.44 12s1.028-2.353 2.295-2.353c1.268 0 2.295 1.053 2.295 2.353");
}

.f6y5q55up {
  fill: var(--svg-color--1f3464, #1f3464);
  d: path("M10.461 11.965c0-1.935 1.013-3.326 1.54-3.78a5.24 5.24 0 0 1 1.556 3.78A5.77 5.77 0 0 1 12 15.817a5.5 5.5 0 0 1-1.539-3.852");
}

.ft5dv1b6b {
  fill: none;
}

.vs4t_tlny {
  fill: var(--svg-color--da1157, #da1157);
  fill-rule: evenodd;
  d: path("M13.53 12c0 2.982-2.357 5.4-5.265 5.4S3 14.982 3 12s2.357-5.4 5.265-5.4S13.53 9.017 13.53 12m-2.97 0c0 1.3-1.028 2.354-2.295 2.354C6.997 14.354 5.97 13.3 5.97 12s1.027-2.353 2.295-2.353c1.267 0 2.295 1.053 2.295 2.353");
}

</style>
