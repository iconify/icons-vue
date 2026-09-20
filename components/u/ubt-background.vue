<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG5wa8wbjW)" class="r4i437pya"/><path class="rcy3z_y-p"/></g><defs><linearGradient id="SVG5wa8wbjW" x1="17.768" x2="6.463" y1="6.254" y2="17.631" gradientUnits="userSpaceOnUse"><stop class="jhl5_6blw"/><stop offset=".22" class="n0z3adckj"/><stop offset=".45" class="rvmki439c"/><stop offset=".71" class="ozzad3bdh"/><stop offset="1" class="gphtemtom"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ubt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gphtemtom {
  stop-color: var(--svg-color--da1e74, #da1e74);
}

.jhl5_6blw {
  stop-color: var(--svg-color--f5e710, #f5e710);
}

.n0z3adckj {
  stop-color: var(--svg-color--4db15a, #4db15a);
}

.ozzad3bdh {
  stop-color: var(--svg-color--1e548a, #1e548a);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rcy3z_y-p {
  fill: var(--svg-color--fff, #fff);
  d: path("m20 6l-2-2h-8v13H7V6H4v12l2 2h5l2-2h5l2-2v-4l-1-1l1-1zm-7 1h4v3h-4zm4 8h-4v-3h4z");
}

.rvmki439c {
  stop-color: var(--svg-color--00a09a, #00a09a);
}

</style>
