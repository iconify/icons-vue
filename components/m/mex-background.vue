<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGYaN5JbTI)" class="r4i437pya"/><path class="mkju3_vqq"/></g><defs><linearGradient id="SVGYaN5JbTI" x1="7.065" x2="7.065" y1="8.201" y2="15.799" gradientUnits="userSpaceOnUse"><stop class="fi71a7btv"/><stop offset="1" class="g7ask0mfb"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mex-background" /></template>
<style>
.fi71a7btv {
  stop-color: var(--svg-color--213973, #213973);
}

.ft5dv1b6b {
  fill: none;
}

.g7ask0mfb {
  stop-color: var(--svg-color--02094b, #02094b);
}

.mkju3_vqq {
  fill: var(--svg-color--fff, #fff);
  d: path("m6.416 8.72l.801-.519l.753.519l-.753.457zm-1.36.754l-.8.519l.8.457l.753-.457zM4 10.2v3.75l3.2 1.85v-3.701zm3.217-.726l-.8.519l.8.457l.753-.457zm-.8 1.792l.8-.52l.753.52l-.753.457zm-.293-1.152l-.8.52l.8.457l.753-.458zm1.361.52l.801-.52l.753.52l-.752.457zm1.893-1.16l-.801.519l.801.457l.753-.457zM10.4 14.2v-4h.8l1.2 2.654l1.2-2.655h2.8v.8h-2.009v.8h2.01v.8h-2.01v.8h2.01v.55l1.245-1.83l-1.244-1.92h.974l.766 1.195l.73-1.195h1.047l-1.262 1.92L20 14.2h-1.01l-.848-1.345l-.838 1.345H13.6v-2.08l-.8 2.08H12l-.8-2.08v2.08z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
