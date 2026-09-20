<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGAyMojeFg)" class="r4i437pya"/><path class="xdylbkh_t"/></g><defs><linearGradient id="SVGAyMojeFg" x1="12.002" x2="12.002" y1="4.002" y2="19.994" gradientUnits="userSpaceOnUse"><stop class="fs_z0kbnl"/><stop offset=".27" class="e6-botbeb"/><stop offset=".46" class="re24tcbmb"/><stop offset="1" class="yyf4iib-l"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:srcx-background" /></template>
<style>
.e6-botbeb {
  stop-color: var(--svg-color--d11ef8, #d11ef8);
}

.fs_z0kbnl {
  stop-color: var(--svg-color--5e189b, #5e189b);
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.re24tcbmb {
  stop-color: var(--svg-color--6b78fb, #6b78fb);
}

.xdylbkh_t {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.839 4.112a.525.525 0 0 1 .754.125l2.574 3.708l2.234-3.688a.525.525 0 0 1 .754-.15c.25.18.31.54.14.8L12.847 8.92l.37.54l3.358-5.213a.526.526 0 0 1 .76-.13c.24.18.299.54.124.8l-3.568 5.517l.6.87l4.522-7.052a.524.524 0 0 1 .75-.14c.25.18.31.54.135.8l-4.728 7.366l4.723 6.806a.596.596 0 0 1-.115.8a.527.527 0 0 1-.76-.125L8.718 4.912a.59.59 0 0 1 .12-.8m-4.613 0a.525.525 0 0 1 .76.12l7.626 10.844l2.933 3.998a.585.585 0 0 1-.095.8a.52.52 0 0 1-.76-.1l-2.498-3.398l-2.324 3.383a.53.53 0 0 1-.76.125a.59.59 0 0 1-.12-.8l2.514-3.653l-.344-.485l-3.579 4.833a.52.52 0 0 1-.76.1a.59.59 0 0 1-.094-.8l3.763-5.087l-.53-.75l-4.712 6.532c-.18.25-.52.3-.76.11a.59.59 0 0 1-.1-.8l4.897-6.796l-5.177-7.371a.6.6 0 0 1 .115-.8zm2.164 0a.525.525 0 0 1 .76.12l10.569 14.847a.59.59 0 0 1-.105.8c-.24.19-.58.14-.76-.115L6.286 4.917a.59.59 0 0 1 .105-.8zm6.612 1.64a.75.75 0 1 1-1.499 0a.75.75 0 0 1 1.499 0m-.75 13.242a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.yyf4iib-l {
  stop-color: var(--svg-color--31a8fa, #31a8fa);
}

</style>
