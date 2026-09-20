<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGyVJt2CpW)" class="r4i437pya"/><path class="tawxvojyd"/></g><defs><linearGradient id="SVGyVJt2CpW" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="p4q25z16a"/><stop offset="1" class="jcsppz9dw"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zap-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jcsppz9dw {
  stop-color: var(--svg-color--50c0fe, #50c0fe);
}

.p4q25z16a {
  stop-color: var(--svg-color--087ffe, #087ffe);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.tawxvojyd {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.024 9.5V4.631c.024-.12-.021-.405-.395-.58c-.325-.153-.68.073-.786.22c-1.623 2.592-4.652 8.045-4.77 8.319c-.15.346-.048.561.094.72c.106.12.358.19.494.19h3.293l-.703 5.956c.01.138.124.436.502.526c.377.09.637-.182.72-.33l5.384-9.11c.078-.12.24-.439.068-.72a.7.7 0 0 0-.623-.322z");
}

</style>
