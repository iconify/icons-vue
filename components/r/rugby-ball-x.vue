<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_29jsbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rugby-ball-x" /></template>
<style>
.y_29jsbzs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.73 17.626q-.554.389-1.139.731t-1.197.631q-.612.291-1.247.528q-.634.238-1.286.421t-1.318.311q-.665.127-1.339.198t-1.351.084q-.677.014-1.353-.03q-.027-.424-.032-.849t.012-.85t.058-.848t.103-.844t.148-.837t.191-.828q.107-.411.236-.817q.128-.405.278-.803q.15-.397.321-.787q.171-.389.362-.769q.191-.379.403-.748q.211-.369.441-.726q.231-.358.48-.702q.249-.345.516-.675t.551-.647t.585-.617t.617-.585t.647-.551t.675-.516t.702-.48t.726-.441q.369-.212.748-.403q.38-.191.769-.362q.39-.171.787-.321q.398-.15.803-.278q.406-.129.817-.236q.412-.106.828-.191q.417-.085.837-.148q.421-.062.844-.103t.848-.058t.85-.012t.849.032q.043.671.03 1.342q-.013.672-.082 1.34q-.069.669-.194 1.329t-.305 1.308t-.414 1.277t-.519 1.238t-.621 1.19q-.336.583-.719 1.135M9 15l6-6m-5.25 2.75l2.5 2.5m-.5-4.5l2.5 2.5m1.25 3.25l5 5m0-5l-5 5");
}

</style>
