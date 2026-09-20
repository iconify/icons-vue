<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGAUeBAe1b)" class="r4i437pya"/><path class="dztclugat"/><path class="g_p3gebfd"/><path clip-rule="evenodd" class="hh47gxqzw"/></g><defs><linearGradient id="SVGAUeBAe1b" x1="4.003" x2="21.535" y1="12.502" y2="12.502" gradientUnits="userSpaceOnUse"><stop class="lwjj23boh"/><stop offset="1" class="xj5vtbt4h"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:x2y2-background" /></template>
<style>
.dztclugat {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.6 7.488a6.86 6.86 0 0 0-4.849-1.985c-3.73 0-6.749 2.91-6.749 6.5s3.02 6.499 6.75 6.499c1.904 0 3.624-.76 4.849-1.985a7.998 7.998 0 1 1 0-9.034z");
}

.ft5dv1b6b {
  fill: none;
}

.g_p3gebfd {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.75 18.002c3.45 0 6.25-2.685 6.25-6s-2.8-6-6.25-6c-1.614 0-3.084.59-4.194 1.55c.765-.4 1.64-.55 2.57-.55c3 0 5.374 2.07 5.374 5s-2.37 5.54-5.374 5.54q-.51 0-.99-.09c.795.35 1.68.55 2.615.55");
}

.hh47gxqzw {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12.25 17.002a4.749 4.749 0 1 0 .001-9.498a4.749 4.749 0 0 0 0 9.498m0-1.5a3.25 3.25 0 1 0 .001-6.499a3.25 3.25 0 0 0 0 6.499");
}

.lwjj23boh {
  stop-color: var(--svg-color--02dffc, #02dffc);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.xj5vtbt4h {
  stop-color: var(--svg-color--5831c9, #5831c9);
}

</style>
