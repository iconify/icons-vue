<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGLVnjUcHz)" class="r4i437pya"/><path class="s0-czn89p"/><path clip-rule="evenodd" class="ubh98c8di"/></g><defs><linearGradient id="SVGLVnjUcHz" x1="98.066" x2="98.02" y1="3.69" y2="34.532" gradientUnits="userSpaceOnUse"><stop class="a8gxrxckj"/><stop offset=".93" class="c7qbrgb2c"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:polyx-background" /></template>
<style>
.a8gxrxckj {
  stop-color: var(--svg-color--ff2e72, #ff2e72);
}

.c7qbrgb2c {
  stop-color: var(--svg-color--4a125e, #4a125e);
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.s0-czn89p {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.861 12c.923 0 1.962-.39 1.962-1.412c0-.983-.997-1.411-1.962-1.411h-2.743v-.942h2.89c1.514 0 2.757.767 2.757 2.353s-1.304 2.353-2.758 2.353H11.06v3.294h-.941V12z");
}

.ubh98c8di {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16m0-.941a7.06 7.06 0 1 0 0-14.12a7.06 7.06 0 0 0 0 14.12");
}

</style>
