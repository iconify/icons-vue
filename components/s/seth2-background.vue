<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGP3fZkeEy)" class="r4i437pya"/><path class="mwu0kwb5h"/><path class="e-2dt96so"/></g><defs><linearGradient id="SVGP3fZkeEy" x1="18.588" x2="14.065" y1="8" y2="20.601" gradientUnits="userSpaceOnUse"><stop class="njmyrab_j"/><stop offset="1" class="v5kabuzto"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:seth2-background" /></template>
<style>
.e-2dt96so {
  fill: var(--svg-color--fff, #fff);
  d: path("m12 13.41l-3.764-2.117l-2.823 5.412zm0 0l3.765-2.117l2.823 5.412zM12 20v-6.588l-6.587 3.294zm0 0v-6.588l6.588 3.294z");
}

.ft5dv1b6b {
  fill: none;
}

.mwu0kwb5h {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 13.411V4l-3.765 7.294zm0 0V4l3.765 7.294z");
}

.njmyrab_j {
  stop-color: var(--svg-color--7dc371, #7dc371);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.v5kabuzto {
  stop-color: var(--svg-color--6fb063, #6fb063);
}

</style>
