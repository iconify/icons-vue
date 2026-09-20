<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGfuh7odwA)" class="r4i437pya"/><path clip-rule="evenodd" class="xmpaczbpr"/></g><defs><linearGradient id="SVGfuh7odwA" x1="4" x2="20" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="h35nacbyr"/><stop offset="1" class="gb-x_zb_s"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:om-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gb-x_zb_s {
  stop-color: var(--svg-color--fe95ce, #fe95ce);
}

.h35nacbyr {
  stop-color: var(--svg-color--ffb298, #ffb298);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.xmpaczbpr {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m5.5 10.5l.333.32l-.333.317l-.333-.317zm-.277 1.217c.154.146.4.146.554 0l.89-.884l.333.25V13.5h-.333v-2.097l-.557.524a.88.88 0 0 1-.61.24a.88.88 0 0 1-.61-.24l-.557-.527v2.1H4v-2.417l.333-.25zM7.167 13.5l1.09-2.667h.49L9.833 13.5h-.366l-.28-.667H7.833l-.286.667zm1.32-2.333L7.943 12.5H9.07l-.563-1.333zM12 12.93h-.02l-1.587-2.097H10V13.5h.333v-2.16h.024L12 13.497l.333.003v-2.667H12zm.667-1.767v-.33H15v.334h-1V13.5h-.333v-2.333h-1zm2.666-.33h1.13c.567 0 .87.307.87.734v.053c0 .4-.183.507-.393.567v.023c.24.01.393.147.393.487v.803H17v-.763c0-.237-.26-.237-.467-.237h-.866v1h-.334zm2 2.667l1.09-2.667h.49L20 13.5h-.367l-.28-.667H18l-.287.667zm-1.666-1.333h.746c.334 0 .587-.257.587-.5c0-.244-.243-.5-.6-.5h-.733zm2.443.333l.543-1.333h.02l.564 1.333z");
}

</style>
