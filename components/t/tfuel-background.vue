<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGyGIAOcQE)" class="r4i437pya"/><path clip-rule="evenodd" class="m6idcgh5n"/></g><defs><linearGradient id="SVGyGIAOcQE" x1="14.791" x2="6.349" y1="5.131" y2="16.686" gradientUnits="userSpaceOnUse"><stop class="q94r0s-nq"/><stop offset="1" class="k4ntd84as"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tfuel-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k4ntd84as {
  stop-color: var(--svg-color--f2a23e, #f2a23e);
}

.m6idcgh5n {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12.346 20c-2.04-.4-6.084-2.216-5.948-6.256h.008c-.04-.8.328-2.812 2.124-4.44C10.778 7.268 11.286 6.588 11.194 4c.82.48 2.46 1.924 2.5 3.84a7.3 7.3 0 0 1-.344 1.9c-.324.952.212 1.752 1.012 1.792c.808.036 1.4-.524 1.452-1.512c.64.64 1.896 2.368 1.784 4.176c-.144 2.26-1.268 3.068-1.968 3.496c-.215.133-.502.241-.82.362c-.86.327-1.947.74-2.464 1.946M15.57 5.816v.576c-.004.096-.092.372-.4.684c-.304.316-.38.8-.38 1a1.38 1.38 0 0 0 .944 1.316c.104-.278.29-.518.532-.688c.32-.176.328-.568.32-.76a3.82 3.82 0 0 0-1.016-2.128M8.8 12.4V14h2.4v2.8h1.6V14h2.4v-1.6z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q94r0s-nq {
  stop-color: var(--svg-color--ee6833, #ee6833);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
