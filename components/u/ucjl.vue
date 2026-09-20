<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGo6Zyzb4e)" class="inrka6biu"/><path fill="url(#SVGO2eIycdX)" class="nwn2prb-l"/><path class="t65xa1dto"/><path class="myyq3ninp"/><path class="qwxri5pan"/><defs><linearGradient id="SVGo6Zyzb4e" x1="20.437" x2="3.844" y1="12" y2="12.281" gradientUnits="userSpaceOnUse"><stop class="zm-0hvvbp"/><stop offset="1" class="nelfhdcqn"/></linearGradient><linearGradient id="SVGO2eIycdX" x1="15.938" x2="7.782" y1="5.812" y2="18.188" gradientUnits="userSpaceOnUse"><stop class="h9arrpisl"/><stop offset="1" class="ukxfx5mzs"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ucjl" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h9arrpisl {
  stop-color: var(--svg-color--b0aeff, #b0aeff);
}

.inrka6biu {
  d: path("M12 19.875a7.875 7.875 0 1 0 0-15.75a7.875 7.875 0 0 0 0 15.75M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.myyq3ninp {
  fill: var(--svg-color--d5dbfb, #d5dbfb);
  d: path("m15.376 7.5l-2.813 1.969V16.5l2.813-1.687z");
}

.nelfhdcqn {
  stop-color: var(--svg-color--975dfe, #975dfe);
}

.nwn2prb-l {
  d: path("M12 19.875a7.875 7.875 0 1 0 0-15.75a7.875 7.875 0 0 0 0 15.75");
}

.qwxri5pan {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.313 10.313c-.562 0-1.592-.377-1.688-.563v6.75c.096.281.563.844 1.688.844s1.969-.563 2.25-.844V9.47c-.563.281-1.536.844-2.25.844");
}

.t65xa1dto {
  fill: var(--svg-color--d7e6f9, #d7e6f9);
  d: path("M12.563 9.469V6.094l-3.938 2.25V9.75c.282.281.788.563 1.688.563s1.873-.563 2.25-.844");
}

.ukxfx5mzs {
  stop-color: var(--svg-color--278edd, #278edd);
}

.zm-0hvvbp {
  stop-color: var(--svg-color--17c8fa, #17c8fa);
}

</style>
