<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="dyd4hr93x"/><path class="kjsxu290t"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nuls-background" /></template>
<style>
.dyd4hr93x {
  fill: var(--svg-color--00e789, #00e789);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.kjsxu290t {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.794 14.692L12 16.365V20l-4.423-2.131V8.504a.47.47 0 0 1 .144-.362l.523-.47a.48.48 0 0 1 .708.072l4.029 5.738l2.236 1.472V7.056l-2.01-1.07v4.959L12 9.449V4l4.423 2.224v9.329l-.884.896l-3.258-1.914l-3.498-4.97v7.56l2.01.977z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
