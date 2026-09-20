<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGKn99HeiT"><path class="k5-vjlrin"/><g transform="translate(3 3)"><circle class="e8g3_dbwu"/><circle class="id90wxvtx"/><circle class="rbpbj-bpt"/><path clip-rule="evenodd" class="wqfzzmg0q"/><circle class="e8g3_dbwu"/><circle class="id90wxvtx"/><circle class="rbpbj-bpt"/><path clip-rule="evenodd" class="mpmtjxabp"/></g></mask></defs><circle mask="url(#SVGKn99HeiT)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:text-bubble-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.e8g3_dbwu {
  cx: 7px;
  cy: 9px;
  r: 1px;
  fill: var(--svg-color--000, #000);
}

.ft5dv1b6b {
  fill: none;
}

.id90wxvtx {
  cx: 10px;
  cy: 9px;
  r: 1px;
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.mpmtjxabp {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M1 6v6.102A3 3 0 0 0 3.864 15.1c.36 1.224.894 1.901 1.84 1.901c.757 0 1.684-.609 3.13-1.898H16a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3H4a3 3 0 0 0-3 3m7.064 7.102l-.286.26c-.864.786-1.543 1.304-1.869 1.522a5.6 5.6 0 0 1-.283-.986l-.166-.796H4a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v6.102a1 1 0 0 1-1 1z");
}

.rbpbj-bpt {
  cx: 13px;
  cy: 9px;
  r: 1px;
  fill: var(--svg-color--000, #000);
}

.wqfzzmg0q {
  fill-rule: evenodd;
  stroke: var(--svg-color--000, #000);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v6.102a2 2 0 0 1-2 2H8.45S6.364 16 5.705 16s-1.056-1.898-1.056-1.898H4a2 2 0 0 1-2-2z");
}

</style>
