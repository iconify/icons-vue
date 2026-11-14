<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s_1x1kmyg"/><path class="h6nhfobes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:parking-fee-paid" /></template>
<style>
.h6nhfobes {
  d: path("M13.5 9c0-1.25-1-1.5-2.5-1.5s-2.5.75-2.5 2c0 2.5 5 1.5 5 4c0 1.25-1 2-2.5 2S8.5 15 8.5 14M11 6v11m3.75 1l2 2L21 15.75");
}

.s_1x1kmyg {
  d: path("M11.851 19H2.5v-5q.123 0 .245-.012t.243-.036t.237-.06q.118-.036.231-.083t.222-.105t.21-.126t.197-.146q.095-.078.182-.165t.165-.181q.078-.095.146-.197t.126-.211t.105-.222t.082-.231q.036-.117.06-.237q.024-.121.036-.243t.012-.245t-.012-.245t-.036-.243q-.024-.12-.06-.237q-.035-.118-.082-.231t-.105-.222t-.126-.211t-.146-.197t-.165-.181t-.182-.165t-.197-.146t-.21-.126t-.222-.105t-.231-.083t-.237-.06q-.121-.024-.243-.036T2.5 9V4h17v5q-.123 0-.245.012t-.243.036t-.237.06q-.118.036-.231.083t-.222.105t-.21.126t-.197.146t-.182.165t-.165.181t-.146.197t-.126.211t-.105.222t-.082.231t-.06.237q-.024.121-.036.243t-.012.245q0 .103.009.206q.008.102.025.204t.042.202t.059.197q.033.098.074.192q.042.094.091.185t.105.177q.056.087.119.168t.133.158q.069.076.145.146t.157.133q.081.064.167.12q.086.057.176.106q.091.05.185.091q.094.042.192.076q.097.034.197.06");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
