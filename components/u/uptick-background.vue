<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="zxui6x_dm"/><path fill="url(#SVGBXQokdXZ)" class="jqni_vb1p"/><path class="g1p2zg0sk"/></g><defs><linearGradient id="SVGBXQokdXZ" x1="13.495" x2="13.495" y1="19.498" y2="9.528" gradientUnits="userSpaceOnUse"><stop/><stop offset=".999" class="v1g637jgr"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:uptick-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g1p2zg0sk {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.4 6.983l-4.717 4.541a.15.15 0 0 1-.21-.004L7.661 9.65a.15.15 0 0 1 .004-.21l3.906-3.764a.149.149 0 0 0-.106-.256H8.212a.16.16 0 0 0-.106.041l-4.06 3.915a.15.15 0 0 0-.005.21l5.372 5.537c.055.06.15.06.21.005l6.55-6.314a.15.15 0 0 0 .005-.21L14.61 6.988c-.06-.06-.15-.064-.21-.005m-2.287-2.572l-1.348-1.389a.073.073 0 0 0-.105 0l-1.45 1.39c-.046.045-.014.127.05.127h2.797c.064 0 .1-.082.055-.128");
}

.jqni_vb1p {
  d: path("m13.753 20.953l-3.589-3.7a.15.15 0 0 0-.21-.005l-1.138 1.096a.15.15 0 0 1-.21-.004l-1.573-1.617a.15.15 0 0 1 .005-.21l7.348-7.081a.15.15 0 0 1 .21.004l5.363 5.533a.15.15 0 0 1-.005.21l-5.995 5.779a.14.14 0 0 1-.206-.005m-1.751-5.468l1.81 1.868a.15.15 0 0 0 .211.005l2.324-2.239a.15.15 0 0 0 .005-.21l-1.81-1.868a.15.15 0 0 0-.211-.005l-2.324 2.239a.14.14 0 0 0-.005.21");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.v1g637jgr {
  stop-color: var(--svg-color--2a005a, #2a005a);
}

.zxui6x_dm {
  fill: var(--svg-color--7800f4, #7800f4);
  d: path("M24 0H0v24h24z");
}

</style>
