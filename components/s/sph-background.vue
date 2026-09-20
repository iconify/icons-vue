<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="exd180bdt"/><path class="k97x1-bch"/><path class="fynhgwbwa"/><path class="c4mz75bgz"/><path class="vcr9xfqpi"/><path class="x6p8c3bqu"/><path class="mkturgelu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sph-background" /></template>
<style>
.c4mz75bgz {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 16.6c.32-.25.5-.54.5-.85s-.18-.6-.5-.85c-.32.25-.5.54-.5.85s.18.6.5.85");
}

.exd180bdt {
  fill: var(--svg-color--ccb806, #ccb806);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.fynhgwbwa {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.5 17.5c2.21 0 4-.784 4-1.75S17.71 14 15.5 14s-4 .784-4 1.75s1.79 1.75 4 1.75");
}

.k97x1-bch {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.001 13a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9M8.5 17.5c2.21 0 4-.784 4-1.75S10.71 14 8.5 14s-4 .784-4 1.75s1.79 1.75 4 1.75");
}

.mkturgelu {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.115 16.5c-.645.59-2.02 1-3.615 1h-.115c.645-.59 2.02-1 3.615-1z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vcr9xfqpi {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 20c2.21 0 4-.784 4-1.75c0-.967-1.79-1.75-4-1.75s-4 .783-4 1.75C8 19.216 9.79 20 12 20");
}

.x6p8c3bqu {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.616 17.5H15.5c-1.595 0-2.97-.41-3.615-1H12c1.595 0 2.97.41 3.615 1");
}

</style>
