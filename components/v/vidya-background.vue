<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="qjjvi7mfl"/><path class="xtgx7kb1j"/><path class="c5mdsjbcq"/><path class="tkstofbyt"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vidya-background" /></template>
<style>
.c5mdsjbcq {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.88 4.047q.133.056.118.212v11.186q.002.17-.023.32l-.052.315L5.4 6.922v-.014zm.119 13.142v2.353c0 .146.014.263.066.348q-.016.077-.052.104c-.02.009-.033.009-.043-.01q-3.744-6.58-7.496-13.158h.014l7.51 10.368z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qjjvi7mfl {
  fill: var(--svg-color--c474e7, #c474e7);
  d: path("M24 0H0v24h24z");
}

.tkstofbyt {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.064 19.892a.63.63 0 0 1-.07-.348a62 62 0 0 0 0-2.353C14.502 13.741 17 10.292 19.5 6.838c.005-.01.014-.01.019-.005c.01 0 .01.01.004.019l-7.29 12.777a2 2 0 0 1-.164.263z");
}

.xtgx7kb1j {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.923 16.08l.052-.315a1.7 1.7 0 0 0 .024-.32V5.016c0-.254-.02-.508 0-.757q.015-.156-.118-.212q.085-.068.15-.038l6.551 2.89q.022.012.01.033l-6.57 9.223q-.016.023-.038.01q-.041-.015-.06-.085");
}

</style>
