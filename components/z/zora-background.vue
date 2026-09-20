<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVG3wgDEcPn)" class="y-c31qnrx"/></g><defs><radialGradient id="SVG3wgDEcPn" cx="0" cy="0" r="1" gradientTransform="translate(15.632 8.3)scale(-13.5137)" gradientUnits="userSpaceOnUse"><stop offset=".007" class="hgyx8tbrw"/><stop offset=".191" class="vuduq_qff"/><stop offset=".498" class="b1us-j39q"/><stop offset=".667" class="vx_pzxb1m"/><stop offset=".823" class="skwjq9bhm"/><stop offset="1" class="bcvbozwiw"/></radialGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zora-background" /></template>
<style>
.b1us-j39q {
  stop-color: var(--svg-color--4281d3, #4281d3);
}

.bcvbozwiw {
  stop-color: var(--svg-color--8f6b40, #8f6b40);
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.hgyx8tbrw {
  stop-color: var(--svg-color--f2cefe, #f2cefe);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.skwjq9bhm {
  stop-color: var(--svg-color--230101, #230101);
}

.vuduq_qff {
  stop-color: var(--svg-color--afbaf1, #afbaf1);
}

.vx_pzxb1m {
  stop-color: var(--svg-color--2e427d, #2e427d);
}

.y-c31qnrx {
  d: path("M12 20a8 8 0 1 1 0-16a8 8 0 0 1 0 16");
}

</style>
