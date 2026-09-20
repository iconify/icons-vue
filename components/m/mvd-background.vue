<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bybupwg5g"/><path class="txuc50b_p"/><path class="g2q8w2m2t"/><path class="q_fw2wbfj"/><path class="k1pj96brn"/><path class="nyha7xuam"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mvd-background" /></template>
<style>
.bybupwg5g {
  fill: var(--svg-color--ffaa27, #ffaa27);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.g2q8w2m2t {
  fill: var(--svg-color--fff, #fff);
  d: path("m4 12l4-4V4L4 8z");
}

.k1pj96brn {
  fill: var(--svg-color--fff, #fff);
  d: path("m19.999 12l-4-4V4l4 4z");
}

.nyha7xuam {
  fill: var(--svg-color--fff, #fff);
  d: path("m18 10l2 2V8zm-6 2l4-4V4l-4 4.07z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q_fw2wbfj {
  fill: var(--svg-color--fff, #fff);
  d: path("m6 10l-2 2V8zm6 2L8 8V4l4 4.07zm8-4l-8 8v4l8-8z");
}

.txuc50b_p {
  fill: var(--svg-color--fff, #fff);
  d: path("m4 8l8 8v4l-8-8z");
}

</style>
