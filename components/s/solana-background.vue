<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGRoz4qc2h)" class="r4i437pya"/><path class="sfa19hb_f"/></g><defs><linearGradient id="SVGRoz4qc2h" x1="4.001" x2="20.408" y1="50.258" y2="50.108" gradientUnits="userSpaceOnUse"><stop class="xnhgfvelh"/><stop offset="1" class="e95k-_nlt"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:solana-background" /></template>
<style>
.e95k-_nlt {
  stop-color: var(--svg-color--47f8c3, #47f8c3);
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

.sfa19hb_f {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.7 8.358a.55.55 0 0 1-.365.145H4.515c-.455 0-.684-.52-.37-.825l2.106-2.03a.54.54 0 0 1 .364-.15h12.87c.46 0 .685.524.365.83zm0 10.005c-.1.09-.23.14-.365.14H4.515c-.455 0-.684-.516-.37-.82l2.106-2.036a.53.53 0 0 1 .364-.145h12.87c.46 0 .685.52.365.825zm0-7.72a.55.55 0 0 0-.365-.14H4.515c-.455 0-.684.515-.37.82l2.106 2.035c.1.091.23.143.364.144h12.87c.46 0 .685-.52.365-.824z");
}

.xnhgfvelh {
  stop-color: var(--svg-color--599db0, #599db0);
}

</style>
