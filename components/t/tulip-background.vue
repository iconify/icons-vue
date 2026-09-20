<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path fill="url(#SVG0NHzUbvx)" class="eo_ak1dyf"/><path fill="url(#SVGqrrrB63B)" class="aokmlgb3t"/><path fill="url(#SVGrTUVge3v)" class="s5g54klqm"/><path fill="url(#SVGNgjhIcTv)" class="k3ve97z8b"/></g><defs><linearGradient id="SVG0NHzUbvx" x1="6.994" x2="17.084" y1="21.577" y2="21.294" gradientUnits="userSpaceOnUse"><stop class="wi7iq848b"/><stop offset="1" class="h2caqob_s"/></linearGradient><linearGradient id="SVGqrrrB63B" x1="12" x2="12" y1="3.537" y2="15.016" gradientUnits="userSpaceOnUse"><stop class="fcwq8gbdq"/><stop offset=".5" class="b9126b2qb"/><stop offset="1" class="h52_74aeo"/></linearGradient><linearGradient id="SVGrTUVge3v" x1="7.144" x2="13.005" y1="4.898" y2="14.622" gradientUnits="userSpaceOnUse"><stop class="fcwq8gbdq"/><stop offset=".5" class="b9126b2qb"/><stop offset="1" class="h52_74aeo"/></linearGradient><linearGradient id="SVGNgjhIcTv" x1="16.869" x2="11.008" y1="4.913" y2="14.637" gradientUnits="userSpaceOnUse"><stop class="fcwq8gbdq"/><stop offset=".5" class="b9126b2qb"/><stop offset="1" class="h52_74aeo"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tulip-background" /></template>
<style>
.aokmlgb3t {
  d: path("M12.7 4.35c2.734 3.548 1.723 7.466-.014 9.844a.847.847 0 0 1-1.385 0c-1.756-2.328-2.94-6.122-.01-9.843a.883.883 0 0 1 1.409 0");
  opacity: var(--svg-opacity--0-45, 0.45);
}

.b9126b2qb {
  stop-color: var(--svg-color--5f7dc1, #5f7dc1);
}

.eo_ak1dyf {
  d: path("M11.543 14.445v2.95C10.477 15.5 8.113 14.7 6.513 14.7C6.514 18.615 9.774 20 12 20c2.23 0 5.486-1.385 5.486-5.299c-1.6 0-3.964.8-5.029 2.693v-2.94a1 1 0 0 1-.914-.009");
  opacity: var(--svg-opacity--0-45, 0.45);
}

.fcwq8gbdq {
  stop-color: var(--svg-color--d141e9, #d141e9);
}

.ft5dv1b6b {
  fill: none;
}

.h2caqob_s {
  stop-color: var(--svg-color--1be6b3, #1be6b3);
}

.h52_74aeo {
  stop-color: var(--svg-color--2bd9b9, #2bd9b9);
}

.k3ve97z8b {
  d: path("M17.08 5.95c.685 4.494-2.049 7.37-4.687 8.531a.87.87 0 0 1-1.23-.667c-.416-2.93.361-6.849 4.673-8.554a.9.9 0 0 1 1.243.686z");
  opacity: var(--svg-opacity--0-45, 0.45);
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s5g54klqm {
  d: path("M8.178 5.255c4.055 1.655 5.042 5.587 4.663 8.549a.87.87 0 0 1-1.225.677c-2.638-1.111-5.46-3.79-4.686-8.545a.9.9 0 0 1 1.248-.686z");
  opacity: var(--svg-opacity--0-45, 0.45);
}

.wi7iq848b {
  stop-color: var(--svg-color--5784c2, #5784c2);
}

</style>
