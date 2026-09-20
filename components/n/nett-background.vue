<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="xx4nfeb2m"/><path class="a384ohbez"/><path class="w58c6-p8h"/><path class="behiby95n"/><path class="u1l1lccge"/><path class="n34rnqbxj"/><path class="lx50f-bck"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nett-background" /></template>
<style>
.a384ohbez {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.577 12l-4.444 5.523c-.156-.091-.142-.347-.12-.466L5.117 12zm3.169 2.263L8.582 12L4.13 17.532c.1.124.352.092.462.055zM8.582 12h-3.47a980 980 0 0 1 1.545-5.459a.57.57 0 0 1 .27-.302z");
}

.behiby95n {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.75 14.277L8.577 12l3.52.188z");
}

.ft5dv1b6b {
  fill: none;
}

.lx50f-bck {
  fill: var(--svg-color--fff, #fff);
  d: path("m15.984 12.457l-3.52-2.565l6.766-3.717c.06-.064.247-.17.513-.091c.265.077.274.393.247.54l-.714 5.833z");
}

.n34rnqbxj {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.29 12.375h-3.338l2.24 5.523c.283-.064.448-.356.485-.49l.612-5.028z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.u1l1lccge {
  fill: var(--svg-color--fff, #fff);
  d: path("m16.024 12.457l-3.932-.283l-.356 2.09l5.656 3.437c.123.083.393.243.512.243c.123 0 .247-.032.297-.046l-2.181-5.44z");
}

.w58c6-p8h {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.425 6.243c-.192-.128-.412-.054-.503 0l1.664 5.761l7.448.453c-2.789-1.993-8.413-6.08-8.61-6.214");
}

.xx4nfeb2m {
  fill: var(--svg-color--54ccff, #54ccff);
  d: path("M24 0H0v24h24z");
}

</style>
