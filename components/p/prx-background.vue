<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGaxhSmcNg)" class="ixc_36b2m"/><path fill="url(#SVGNzGFobSq)" class="ifjlhhb0d"/></g><defs><linearGradient id="SVGaxhSmcNg" x1="6.669" x2="11.484" y1="5.284" y2="14.069" gradientUnits="userSpaceOnUse"><stop class="h4uup7b_z"/><stop offset="1" class="ndt5h9gjs"/></linearGradient><linearGradient id="SVGNzGFobSq" x1="5.981" x2="15.261" y1="6.286" y2="11.466" gradientUnits="userSpaceOnUse"><stop class="h4uup7b_z"/><stop offset="1" class="ndt5h9gjs"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:prx-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.h4uup7b_z {
  stop-color: var(--svg-color--f504cb, #f504cb);
}

.ifjlhhb0d {
  d: path("M7.977 14.537L5.143 20l7.954-5.285L5.143 4z");
}

.ixc_36b2m {
  d: path("M18.857 8.516L5.234 4.086L11.2 12.47z");
}

.ndt5h9gjs {
  stop-color: var(--svg-color--3f2ea0, #3f2ea0);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
