<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kfo42_7ao"/><path class="yz15h4b0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:season-trophy" /></template>
<style>
.kfo42_7ao {
  d: path("M5 3.5h10v5a5 5 0 0 1-10 0Zm5 10v.7m0 1.8v4.5m-4 0h6.8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yz15h4b0d {
  d: path("M5 5.5H2v2q-.008.086-.012.172t-.002.173q.001.086.008.172q.006.086.018.172t.027.17q.016.085.038.169t.047.166t.056.163t.066.16q.035.078.075.155t.083.151t.092.146t.101.14t.108.135q.056.065.116.128q.06.062.123.121t.13.114t.136.106t.142.098t.148.09t.152.081t.157.072q.079.034.16.063q.082.029.164.054q.083.024.167.044t.169.035t.171.024t.172.015t.173.005t.172-.004q.086-.005.172-.015t.171-.025M15 5.5h3v2q.032.329-.008.657m-1.601 2.303q-.216.112-.448.187q-.232.076-.474.113t-.485.034q-.244-.002-.484-.044M17.75 14l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

</style>
