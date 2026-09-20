<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGkPqIrdbj)" class="r4i437pya"/><path class="xk6fhib8q"/><path class="rfd3dbb9h"/><path class="p2bmko55g"/></g><defs><linearGradient id="SVGkPqIrdbj" x1="12" x2="12" y1="4.001" y2="20" gradientUnits="userSpaceOnUse"><stop class="naysk4zao"/><stop offset="1" class="i2d6m_p3f"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ydf-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i2d6m_p3f {
  stop-color: var(--svg-color--fbab1f, #fbab1f);
}

.naysk4zao {
  stop-color: var(--svg-color--eb508f, #eb508f);
}

.p2bmko55g {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.995 8.794a.2.2 0 0 1-.11.18a.23.23 0 0 1-.225-.005l-.69-.465l-3.608 6.602c-1.4-2.679-1.25-4.573.794-8.301l.07-.12l-.59-.39a.2.2 0 0 1 .023-.225a.2.2 0 0 1 .063-.05l3.868-1.994a.23.23 0 0 1 .21 0c.07.04.195.1.195.175z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rfd3dbb9h {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.999 8.504a1 1 0 1 0 0-1.999a1 1 0 0 0 0 1.999m-7.578-.206l-.03.04a1.844 1.844 0 0 0 .46 2.679l3.863 2.619a2.144 2.144 0 0 0 2.864-.43l.03-.04a1.847 1.847 0 0 0-.46-2.679L7.285 7.868a2.144 2.144 0 0 0-2.864.43M14.907 20c-.225 0-.44-.06-.625-.165a1.14 1.14 0 0 1-.434-.45l-1.8-3.448a1.73 1.73 0 0 1 .015-1.64l4.094-7.486c-2.04 3.728-2.2 5.622-.8 8.301l1.234 2.359c.615 1.164-.3 2.529-1.684 2.529");
}

.xk6fhib8q {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.998 9.005a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

</style>
