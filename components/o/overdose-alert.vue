<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="re_pryb9d"/><path class="lk7hxpi0f"/><path class="z8cz9vbei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:overdose-alert" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lk7hxpi0f {
  fill: currentColor;
  d: path("M17 8a1 1 0 1 0 2 0a1 1 0 1 0-2 0m-.416 3.571q-.017-.229.08-.436q.036-.078.087-.148t.115-.127q.064-.059.137-.103q.074-.045.155-.074q.081-.03.166-.043t.171-.009t.17.024q.084.021.162.057l1.586.74q.173.081.296.226");
}

.re_pryb9d {
  d: path("M5.125 6.5h3.75A2.625 2.625 0 0 1 11.5 9.125v2.25A2.625 2.625 0 0 1 8.875 14h-3.75A2.625 2.625 0 0 1 2.5 11.375v-2.25A2.625 2.625 0 0 1 5.125 6.5m7.448 7.864q-.119-.05-.229-.117q-.11-.066-.209-.148t-.185-.177t-.157-.203t-.126-.223q-.055-.117-.092-.24t-.056-.25t-.019-.256v-5q0-.086.008-.172t.026-.169q.016-.085.041-.167t.058-.162q.033-.079.074-.155t.088-.147q.048-.072.102-.138q.055-.067.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041t.169-.026Q13.164 6 13.25 6t.172.008q.085.009.169.026q.085.016.167.041t.162.058q.079.033.155.074t.147.088t.138.102t.127.116q.061.06.116.127q.054.066.102.138q.048.071.088.147q.041.076.074.155q.033.08.058.162t.041.167q.017.084.026.169T15 7.75v4.425M4.5 10.25h5M13.25 6v7.5");
}

.z8cz9vbei {
  d: path("M14.25 18a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0M18 16v2m0 2h.01");
}

</style>
