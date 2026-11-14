<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kmmsohgqb"/><path class="p9fpdvb5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:package-json" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kmmsohgqb {
  d: path("M10.474 17.229q-.156.043-.317.058q-.162.014-.323-.001t-.317-.06q-.155-.045-.3-.117l-5.75-2.875q-.108-.054-.208-.123t-.19-.151q-.09-.081-.167-.175t-.141-.197t-.113-.214t-.082-.228t-.049-.237t-.017-.241V7.332q0-.121.017-.241q.016-.121.049-.237q.033-.117.082-.228t.113-.214t.141-.197t.167-.175t.19-.151t.208-.123l5.75-2.875q.182-.091.381-.138q.198-.047.402-.047t.402.047t.381.138l5.75 2.875q.109.054.208.123q.1.069.19.151t.167.175t.141.197q.064.103.113.214t.082.228t.049.237q.017.12.017.241v3.931");
}

.p9fpdvb5m {
  d: path("M2.5 6.25L10 10l7.5-3.75M10 10v7.5m5.5-4.25h-.25q-1 0-1 1v2.25l-1 1l1 1v2.25q0 1 1 1h.25m4-8.5h.25q1 0 1 1v2.25l1 1l-1 1v2.25q0 1-1 1h-.25");
}

</style>
