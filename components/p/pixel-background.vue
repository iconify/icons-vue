<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG2MT9ltfP)" class="r4i437pya"/><path class="cd1az5btz"/><path class="a3r7t6b6e"/></g><defs><linearGradient id="SVG2MT9ltfP" x1="4" x2="20" y1="8.8" y2="15.54" gradientUnits="userSpaceOnUse"><stop class="ekadlobcu"/><stop offset="1" class="cqxfv7j9h"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pixel-background" /></template>
<style>
.a3r7t6b6e {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.267 11.468h4.267v4.266H8.267z");
}

.cd1az5btz {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.267 15.733h4.267V20H8.267zM12.534 4h1.669A5.8 5.8 0 0 1 20 9.802c0 3.2-2.597 5.93-5.802 5.93h-5.93V7.734h4.266v3.733h1.669c1.05 0 2.064-.816 2.064-1.866s-1.013-1.867-2.07-1.867h-1.663zM4 11.468h4.267v4.266H4z");
}

.cqxfv7j9h {
  stop-color: var(--svg-color--16ddde, #16ddde);
}

.ekadlobcu {
  stop-color: var(--svg-color--3eff6e, #3eff6e);
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

</style>
