<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v6o7gvzmz"/><path class="h201gnb1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pre-release" /></template>
<style>
.h201gnb1o {
  d: path("M2.5 6.25L10 10l7.5-3.75M10 10v7.5m5 4.5v-7.5a2.5 2.5 0 0 1 5 0a2.5 2.5 0 0 1-2.5 2.5a2.5 2.5 0 0 1 0 5c-1 0-1.75-.5-2.5-1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v6o7gvzmz {
  d: path("m12.191 16.405l-1.408.704q-.182.091-.381.138q-.198.047-.402.047t-.402-.047t-.381-.138l-5.75-2.875q-.108-.054-.208-.123t-.19-.151q-.09-.081-.167-.175t-.141-.197t-.113-.214t-.082-.228t-.049-.237t-.017-.241V7.332q0-.121.017-.241q.016-.121.049-.237q.033-.117.082-.228t.113-.214t.141-.197t.167-.175t.19-.151t.208-.123l5.75-2.875q.182-.091.381-.138q.198-.047.402-.047t.402.047t.381.138l5.75 2.875q.109.054.208.123q.1.069.19.151t.167.175t.141.197q.064.103.113.214t.082.228t.049.237q.017.12.017.241v1.831");
}

</style>
