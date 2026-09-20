<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGuT8TBbch)" class="r4i437pya"/><path class="d5377vbny"/><path class="ra_riuxbo"/></g><defs><linearGradient id="SVGuT8TBbch" x1="16.534" x2="7.689" y1="6.248" y2="19.064" gradientUnits="userSpaceOnUse"><stop class="qtabh7b_c"/><stop offset=".28" class="zx6s-cchi"/><stop offset=".59" class="xj5jnhb7t"/><stop offset="1" class="fqbowebnj"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ommi-background" /></template>
<style>
.d5377vbny {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.274 5.519c1.95.15 3.66 1.15 4.755 2.635l1.215-.885a8.03 8.03 0 0 0-5.97-3.25zm-5.475.2a8 8 0 0 0 1.93 13.685l.515-1.41a6.5 6.5 0 0 1-1.5-11.115l-.95-1.16zm6.125 12.68l.25 1.48c2-.35 3.745-1.44 4.94-2.98l-1.105-1.026a6.52 6.52 0 0 1-4.085 2.525M10.766 7c.83 0 1.505-.672 1.505-1.5S11.597 4 10.766 4S9.26 4.672 9.26 5.5S9.935 7 10.766 7");
}

.fqbowebnj {
  stop-color: var(--svg-color--c9d505, #c9d505);
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qtabh7b_c {
  stop-color: var(--svg-color--3ad02c, #3ad02c);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.ra_riuxbo {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.26 13c.555 0 1.005-.448 1.005-1s-.45-1-1.005-1s-1.005.448-1.005 1s.45 1 1.005 1M12 20c.694 0 1.256-.56 1.256-1.25S12.694 17.5 12 17.5s-1.255.56-1.255 1.25S11.307 20 12 20m2.9-5.88a3.007 3.007 0 0 1-4.765-.67l-1.5.35a4.514 4.514 0 0 0 7.33 1.38zm.15-4.08a3.005 3.005 0 0 0-4.885.46h-1.65a4.515 4.515 0 0 1 7.67-1.45z");
}

.xj5jnhb7t {
  stop-color: var(--svg-color--79d41c, #79d41c);
}

.zx6s-cchi {
  stop-color: var(--svg-color--3dd22d, #3dd22d);
}

</style>
