<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zcf-9qb4b"/><path class="xgn106sog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stock-reserved" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xgn106sog {
  d: path("m3 7l9 4.5L21 7m-9 4.5v10M7.5 4.75l9 4.5m.5 5h2a1.5 1.5 0 0 1 1.5 1.5v3.974a.794.794 0 0 1-1.25.651l-.39-.273a1.5 1.5 0 0 0-1.72 0l-.39.273a.794.794 0 0 1-1.25-.651V15.75a1.5 1.5 0 0 1 1.5-1.5");
}

.zcf-9qb4b {
  d: path("m12.898 21.052l-.115.057q-.182.091-.381.138q-.198.047-.402.047t-.402-.047t-.381-.138l-7.25-3.625q-.108-.054-.208-.123t-.19-.151t-.167-.175t-.141-.197t-.113-.214t-.082-.228q-.033-.116-.049-.237Q3 16.039 3 15.918V8.082q0-.121.017-.241q.016-.121.049-.237q.033-.117.082-.228t.113-.214t.141-.197t.167-.175t.19-.151t.208-.123l7.25-3.625q.182-.091.381-.138q.198-.047.402-.047t.402.047t.381.138l7.25 3.625q.108.054.208.123t.19.151t.167.175t.141.197q.064.103.113.214t.082.228t.049.237q.017.12.017.241v3.854");
}

</style>
