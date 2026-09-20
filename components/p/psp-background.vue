<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGJgGHmbIm)" class="r4i437pya"/><path clip-rule="evenodd" class="yjh1rrblw"/></g><defs><linearGradient id="SVGJgGHmbIm" x1="15.86" x2="10.484" y1="6.243" y2="18.698" gradientUnits="userSpaceOnUse"><stop class="ts3-bsa0f"/><stop offset="1" class="mt-tjbjbu"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:psp-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mt-tjbjbu {
  stop-color: var(--svg-color--185bef, #185bef);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.ts3-bsa0f {
  stop-color: var(--svg-color--568eff, #568eff);
}

.yjh1rrblw {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M4 5.5h7l-3.49 6zm1.15 13H20l-7.445-13zm3.19-2h8.32L12.49 9z");
}

</style>
