<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nbypt9boz"/><path class="g43tk4dvd"/><path class="p1c1_lbge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:package-install" /></template>
<style>
.g43tk4dvd {
  d: path("m2.5 6.5l8 4l8-4m-8 4V19m-4-14.5l8 4M14 18a4 4 0 1 0 8 0a4 4 0 1 0-8 0m4-2v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nbypt9boz {
  d: path("M11.185 18.654q-.175.075-.362.11t-.377.029t-.375-.052q-.184-.047-.354-.132l-6.25-3.125q-.108-.054-.208-.123t-.19-.151q-.09-.081-.167-.175t-.141-.197t-.113-.214t-.082-.228t-.049-.237t-.017-.241V7.582q0-.121.017-.241q.016-.121.049-.237q.033-.117.082-.228t.113-.214t.141-.197t.167-.175t.19-.151t.208-.123l6.25-3.125q.182-.091.381-.138q.198-.047.402-.047t.402.047t.381.138l6.25 3.125q.109.054.208.123q.1.069.19.151t.167.175t.141.197q.064.103.113.214t.082.228t.049.237q.017.12.017.241v3.672");
}

.p1c1_lbge {
  d: path("M16.5 18.5L18 20l1.5-1.5");
}

</style>
