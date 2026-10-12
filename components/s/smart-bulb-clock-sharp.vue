<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="fuexkebhx"/><path class="ye74oqbix"/><path class="kowaom1sy"/><path class="wif_zxzyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:smart-bulb-clock-sharp" /></template>
<style>
.fuexkebhx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 17.25v-1.5a3 3 0 0 0-1.1-2.3a6 6 0 1 1 7.7 0a3 3 0 0 0-1.1 2.3v1.5Z");
}

.kowaom1sy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 11.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wif_zxzyy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 20.5h4.5");
}

.ye74oqbix {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 8.75L12 6.591l2.25 2.159");
}

</style>
