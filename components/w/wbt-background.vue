<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGGgrMVd7Q)" class="r4i437pya"/><path clip-rule="evenodd" class="ih0vod1yb"/></g><defs><linearGradient id="SVGGgrMVd7Q" x1="3.995" x2="20" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="kgzmqdb7y"/><stop offset="1" class="zs5f5vaqg"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wbt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ih0vod1yb {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M17.657 17.657A8 8 0 1 1 6.343 6.342a8 8 0 0 1 11.314 11.315m-5.284-8.038a.97.97 0 0 1 .4.312h-.005l1.225 1.602l2.498-6.153c.57.387 1.087.847 1.54 1.366l-2.883 7.105a.97.97 0 0 1-1.673.217l-1.22-1.602l-1.607 3.953a.97.97 0 0 1-.852.608h-.048a.97.97 0 0 1-.857-.518l-2.252-4.255a.972.972 0 0 1 1.72-.905l1.276 2.408l1.46-3.604a.97.97 0 0 1 1.278-.534");
}

.kgzmqdb7y {
  stop-color: var(--svg-color--e9c570, #e9c570);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.zs5f5vaqg {
  stop-color: var(--svg-color--f7b839, #f7b839);
}

</style>
