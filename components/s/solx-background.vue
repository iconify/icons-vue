<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGUlpjMVDF)" class="r4i437pya"/><path class="nti_or-9l"/></g><defs><linearGradient id="SVGUlpjMVDF" x1="19.485" x2="5.98" y1="9.415" y2="15.895" gradientUnits="userSpaceOnUse"><stop offset=".03" class="yd2x-seks"/><stop offset=".61" class="y105d5b8t"/><stop offset="1" class="apxkel6ji"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:solx-background" /></template>
<style>
.apxkel6ji {
  stop-color: var(--svg-color--20bdfc, #20bdfc);
}

.ft5dv1b6b {
  fill: none;
}

.nti_or-9l {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.66 9H14c0-1.32-1.38-1.95-2-2c-.705-.035-2 .385-2 1.615c0 1.535.54 1.26 4.455 2.01c3.135.6 4 3.005 4.04 4.135c.1 1.75-1.04 5.24-6.4 5.24c-5.355 0-6.63-3.295-6.595-5h3.88c-.05 1.74 2.12 2 2.715 2c.6 0 2.405-.35 2.405-1.865s-1.485-1.44-2.065-1.48c-.46-.03-1.15-.115-1.435-.155c-3.9-.515-4.995-3.18-4.995-4.525C6.005 7.625 6.15 4 12 4c4.68 0 5.72 3.34 5.66 5");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.y105d5b8t {
  stop-color: var(--svg-color--483eff, #483eff);
}

.yd2x-seks {
  stop-color: var(--svg-color--e604b7, #e604b7);
}

</style>
