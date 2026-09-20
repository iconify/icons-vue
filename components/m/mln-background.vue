<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGFIKvRbsc)" class="r4i437pya"/><path class="jtuym6s9o"/></g><defs><linearGradient id="SVGFIKvRbsc" x1="12" x2="12" y1="6.811" y2="17.189" gradientUnits="userSpaceOnUse"><stop offset=".24" class="kffun23av"/><stop offset=".66" class="k7si54fov"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mln-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jtuym6s9o {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.514 6.81c-.718 0-1.298.597-1.298 1.332V12H9.622V9.41a.865.865 0 1 0-1.73 0V12H5.73v-.865a.865.865 0 1 0-1.73 0V12h1.73v1.396c0 .662.484 1.198 1.08 1.198c.598 0 1.082-.536 1.082-1.197V12h1.73v3.835a1.33 1.33 0 0 0 1.297 1.354c.718 0 1.297-.606 1.297-1.354V12h2.595v3.04a.86.86 0 0 0 .865.852a.86.86 0 0 0 .865-.852V12h1.73v.864a.865.865 0 1 0 1.729 0V12h-1.73V9.284c0-.41-.389-.744-.865-.744c-.475 0-.864.333-.864.744V12h-1.73V8.142c0-.735-.58-1.331-1.297-1.331");
}

.k7si54fov {
  stop-color: var(--svg-color--01cbbf, #01cbbf);
}

.kffun23av {
  stop-color: var(--svg-color--6f4aef, #6f4aef);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
