<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k36w3-bol"/><path class="pj65upb1m"/><path class="wdpj3cbsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:return-damaged" /></template>
<style>
.k36w3-bol {
  d: path("M14.1 19.5H2.5V3h17v10.1M2.5 8h17");
}

.pj65upb1m {
  d: path("m11 8l-2.5 3.5L12 14l-2 3m11 4.25V19a2.5 2.5 0 0 0-2.5-2.5H15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wdpj3cbsu {
  d: path("m17 14.5l-2 2l2 2");
}

</style>
