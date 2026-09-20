<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGsI1ijErQ)" class="r4i437pya"/><path class="p0dnkvorm"/><path class="a_58dzbvb"/></g><defs><linearGradient id="SVGsI1ijErQ" x1="12" x2="12" y1="4.008" y2="19.997" gradientUnits="userSpaceOnUse"><stop offset=".71" class="q0hvl2e_q"/><stop offset="1" class="uzfc01bhj"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ttk-background" /></template>
<style>
.a_58dzbvb {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.24 11.063a.23.23 0 0 0-.188.094c.094-.96.367-1.867.78-2.7l4.318-.22c-.54.46-1.373.526-1.853.474c.188.565 1.331.706 1.881.706v.705h-1.88v-.235a.235.235 0 1 0-.236.235c-.546.955-1.655 1.143-2.586 1.176a.235.235 0 0 0-.236-.235");
}

.ft5dv1b6b {
  fill: none;
}

.p0dnkvorm {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.416 16.54a7.96 7.96 0 0 1-1.402-4.88c.43.274.904.47 1.402.578zm4.232 3.106a8 8 0 0 1-2.187-1.059h1.717v.47h.47zm.942.229v-.818h.235v-.47h.235v-6.584h-.236v-.47h-.235v-.941h2.822v.94h-.235v.47h-.235v6.585h.235v.47h.235v.818a8 8 0 0 1-2.822 0m5.949-1.288a8 8 0 0 1-2.186 1.058v-.587h.47v-.47zm.635-6.113h-2.821v.94h.235v.47h.235v4.233h1.881v-4.232h.235v-.47h.235zm-7.524 0H6.827v.94h.235v.47h.235v4.233H9.18v-4.232h.235v-.47h.235zm8.464 4.679a7.96 7.96 0 0 0 1.858-5.737h-.01a.24.24 0 0 1-.24.112c-.47.217-1.09.475-1.608.475zm1.835-5.996a.234.234 0 0 0-.366-.018a.24.24 0 0 0-.057.126c-1.308-.132-2.21-.626-2.502-1.157a.236.236 0 0 0-.085-.456c-.235 0-.235.235-.235.235v.235h-2.351v-.705c1.128 0 2.036-.47 2.351-.706c-1.345.047-1.975-.48-2.22-.959a.47.47 0 1 0-.601-.451h-3.763a.471.471 0 1 0-.602.451a1.4 1.4 0 0 1-.367.484l-3.964-.413q.163-.27.348-.522h2.704l-2.394-.4a7.98 7.98 0 0 1 12.472.202l-3.024.433l3.48.216q.149.24.283.49h-2.822l3.038.432a8 8 0 0 1 .682 2.488z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q0hvl2e_q {
  stop-color: var(--svg-color--c9af67, #c9af67);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.uzfc01bhj {
  stop-color: var(--svg-color--a58c51, #a58c51);
}

</style>
