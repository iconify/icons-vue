<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><g transform="translate(3 3)"><circle class="xmogy0_2h"/><circle class="hd7l-yb7d"/><circle class="hedj3bbrm"/><path clip-rule="evenodd" class="m1vi34bfp"/><circle class="xmogy0_2h"/><circle class="hd7l-yb7d"/><circle class="hedj3bbrm"/><path clip-rule="evenodd" class="bj3fbgbuc"/><path class="xtuew9_gn"/></g><path clip-rule="evenodd" class="ksag4bb-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:text-bubble-circle-off" /></template>
<style>
.bj3fbgbuc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1 6v6.102A3 3 0 0 0 3.864 15.1c.36 1.224.894 1.901 1.84 1.901c.757 0 1.684-.609 3.13-1.898H16a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3H4a3 3 0 0 0-3 3m7.064 7.102l-.286.26c-.864.786-1.543 1.304-1.869 1.522a5.6 5.6 0 0 1-.283-.986l-.166-.796H4a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v6.102a1 1 0 0 1-1 1z");
}

.ft5dv1b6b {
  fill: none;
}

.hd7l-yb7d {
  cx: 10px;
  cy: 9px;
  r: 1px;
  fill: currentColor;
}

.hedj3bbrm {
  cx: 13px;
  cy: 9px;
  r: 1px;
  fill: currentColor;
}

.ksag4bb-q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.m1vi34bfp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v6.102a2 2 0 0 1-2 2H8.45S6.364 16 5.705 16s-1.056-1.898-1.056-1.898H4a2 2 0 0 1-2-2z");
}

.xmogy0_2h {
  cx: 7px;
  cy: 9px;
  r: 1px;
  fill: currentColor;
}

.xtuew9_gn {
  fill: currentColor;
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
