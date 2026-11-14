<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy0ffwoxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mortgage-portability" /></template>
<style>
.iy0ffwoxy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.56 15.705q-.06-.223-.06-.455v-4.484q0-.181.037-.359q.037-.177.11-.343t.178-.314t.238-.27l4.75-4.384q.06-.055.125-.105t.134-.093t.142-.08q.073-.036.149-.066t.154-.052q.079-.023.159-.038t.161-.023t.163-.007t.163.007q.081.008.161.023t.159.038q.078.022.154.052t.149.066t.142.08t.134.093t.125.105l4.75 4.384q.133.123.238.27t.178.314t.11.343q.037.178.037.359v4.484q0 .216-.052.425M2.5 10h2m-2 3.5H5M3.5 17H5m3.5 2.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
