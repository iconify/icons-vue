<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGHUYNPcwG)" class="ep7lms8-b"/><path fill="url(#SVG6dNbzcIz)" class="oibxzqdgq"/><path class="d9hw67bjv"/><path class="wcq_libot"/><path class="c0c4o-bwa"/></g><defs><linearGradient id="SVGHUYNPcwG" x1="19.5" x2="4.75" y1="12" y2="12.25" gradientUnits="userSpaceOnUse"><stop class="zm-0hvvbp"/><stop offset="1" class="nelfhdcqn"/></linearGradient><linearGradient id="SVG6dNbzcIz" x1="15.5" x2="8.25" y1="6.5" y2="17.5" gradientUnits="userSpaceOnUse"><stop class="h9arrpisl"/><stop offset="1" class="ukxfx5mzs"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ucjl-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.c0c4o-bwa {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.5 10.5c-.5 0-1.415-.335-1.5-.5v6c.085.25.5.75 1.5.75s1.75-.5 2-.75V9.75c-.5.25-1.365.75-2 .75");
}

.d9hw67bjv {
  fill: var(--svg-color--d7e6f9, #d7e6f9);
  d: path("M12.5 9.75v-3l-3.5 2V10c.25.25.7.5 1.5.5s1.665-.5 2-.75");
}

.ep7lms8-b {
  d: path("M12 19a7 7 0 1 0 0-14a7 7 0 0 0 0 14m0 1a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.ft5dv1b6b {
  fill: none;
}

.h9arrpisl {
  stop-color: var(--svg-color--b0aeff, #b0aeff);
}

.nelfhdcqn {
  stop-color: var(--svg-color--975dfe, #975dfe);
}

.oibxzqdgq {
  d: path("M12 19a7 7 0 1 0 0-14a7 7 0 0 0 0 14");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ukxfx5mzs {
  stop-color: var(--svg-color--278edd, #278edd);
}

.wcq_libot {
  fill: var(--svg-color--d5dbfb, #d5dbfb);
  d: path("m15 8l-2.5 1.75V16l2.5-1.5z");
}

.zm-0hvvbp {
  stop-color: var(--svg-color--17c8fa, #17c8fa);
}

</style>
