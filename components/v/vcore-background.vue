<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ykmdyve6n"/><path clip-rule="evenodd" class="xotvat01c"/><path class="hvlu2_vkm"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vcore-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hvlu2_vkm {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.56 14.612a8 8 0 0 1-2.545 3.622c-.8-.79-1.538-2.634-.63-3.669c.88-1.002 2.399-.432 3.175.047M8.694 19.285a8.03 8.03 0 0 1-3.914-3.839c.63-.235 1.684-.3 2.724.635c1.166 1.054 1.354 2.451 1.19 3.204M6.384 6.31c.658.292 1.52.518 2.164.193l.56-.286c.625-.33.77-.41 1.302-.283c.25.061.452.221.659.381c.339.268.691.546 1.298.41c.875-.198 2.409-1.2 2.409-2.225a7.98 7.98 0 0 0-8.392 1.806z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xotvat01c {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M19.997 12.003a7.997 7.997 0 1 1-15.994 0a7.997 7.997 0 0 1 15.994 0M12.913 7.3h1.882l-1.327 3.293l4.177-1.331v1.797l-2.963.945l2.963.94v1.802l-4.083-1.307l1.318 3.27h-1.882l-.997-2.47l-.998 2.47H9.122l1.355-3.36l-4.121 1.317V12.87L9.07 12l-2.714-.866V9.336l4.215 1.35l-1.364-3.387h1.881l.913 2.263z");
}

.ykmdyve6n {
  fill: var(--svg-color--b38b3e, #b38b3e);
  d: path("M24 0H0v24h24z");
}

</style>
