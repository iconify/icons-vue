<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGHkFPkcaw)" clip-rule="evenodd" class="t14x-z1wp"/><path fill="url(#SVG3sqiNbEl)" class="b3pnagb4m"/><path fill="url(#SVGCSMT3bTi)" class="gdj60poov"/><path class="j6_g9abay"/><defs><linearGradient id="SVGHkFPkcaw" x1="18.618" x2="5.382" y1="5.382" y2="18.618" gradientUnits="userSpaceOnUse"><stop class="gbj8klbjk"/><stop offset="1" class="gsi6p_b6t"/></linearGradient><linearGradient id="SVG3sqiNbEl" x1="2.999" x2="20.364" y1="8" y2="19.719" gradientUnits="userSpaceOnUse"><stop offset=".14" class="i4pkfcbrd"/><stop offset=".35" class="gzh-0c09z"/><stop offset="1" class="jw3xbvbfe"/></linearGradient><linearGradient id="SVGCSMT3bTi" x1="6.599" x2="17.399" y1="4.8" y2="17.4" gradientUnits="userSpaceOnUse"><stop class="bv4gwwb_z"/><stop offset="1" class="i134_2b-z"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nbt" /></template>
<style>
.b3pnagb4m {
  d: path("M16.235 13.98c0 .657-.62 1.197-1.324 1.197s-1.323-.54-1.323-1.197V9.883c0-.794-.46-1.588-1.525-1.588h-.127c-1.064 0-1.525.794-1.525 1.588v4.097c0 .657-.62 1.197-1.323 1.197c-.704 0-1.324-.54-1.324-1.197V9.353c0-2.112 1.906-3.706 4.15-3.706h.128c2.223 0 4.193 1.605 4.193 3.706z");
}

.bv4gwwb_z {
  stop-color: var(--svg-color--dfe8f7, #dfe8f7);
}

.ft5dv1b6b {
  fill: none;
}

.gbj8klbjk {
  stop-color: var(--svg-color--ac89dd, #ac89dd);
}

.gdj60poov {
  d: path("M9.088 8.295a1.324 1.324 0 1 0 0-2.648a1.324 1.324 0 0 0 0 2.648");
}

.gsi6p_b6t {
  stop-color: var(--svg-color--9864e6, #9864e6);
}

.gzh-0c09z {
  stop-color: var(--svg-color--7a73e6, #7a73e6);
}

.i134_2b-z {
  stop-color: var(--svg-color--bbbbf1, #bbbbf1);
}

.i4pkfcbrd {
  stop-color: var(--svg-color--7b72dc, #7b72dc);
}

.j6_g9abay {
  fill: var(--svg-color--2a1f63, #2a1f63);
  d: path("M7.764 16.234h8.47v1.06h-8.47z");
}

.jw3xbvbfe {
  stop-color: var(--svg-color--bc9ceb, #bc9ceb);
}

.t14x-z1wp {
  fill-rule: evenodd;
  d: path("M21 12a9 9 0 1 1-18 0a9 9 0 0 1 18 0m-1.059 0a7.941 7.941 0 1 1-15.883 0a7.941 7.941 0 0 1 15.883 0");
}

</style>
