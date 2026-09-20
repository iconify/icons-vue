<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGS2UmWdtj)" class="r4i437pya"/><path clip-rule="evenodd" class="v05m8cchz"/></g><defs><linearGradient id="SVGS2UmWdtj" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="fklfcua4e"/><stop offset="1" class="ial9f20zk"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rndr-background" /></template>
<style>
.fklfcua4e {
  stop-color: var(--svg-color--e92121, #e92121);
}

.ft5dv1b6b {
  fill: none;
}

.ial9f20zk {
  stop-color: var(--svg-color--9c0403, #9c0403);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.v05m8cchz {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 4.5a7.5 7.5 0 1 1-6.05 3.07A1.495 1.495 0 0 0 8.5 6.5a1.5 1.5 0 1 0-2.855.64A8 8 0 1 0 12 4zm-5 3a1 1 0 1 0 0-2a1 1 0 0 0 0 2m5 8a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7");
}

</style>
