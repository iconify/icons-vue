<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="mgiids75u"/><path class="k-9av2byj"/><path class="nw6_dqolj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:patch-bandage-sharp" /></template>
<style>
.k-9av2byj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.71 7.79h0L14.12 6.2l-1.59 1.59l-4.24 4.24l-1.59 1.59l1.59 1.59l1.59 1.59l1.59-1.59l4.24-4.24l1.59-1.59z");
}

.mgiids75u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.75l6.6 2.45l.652.244l-.002.696v5.26c0 4.4-2.9 7.6-7.25 9.85C7.65 19 4.75 15.8 4.75 11.4V6.14l-.002-.696L5.4 5.2Z");
}

.nw6_dqolj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.3 9.2h.01M9.7 13.8h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
