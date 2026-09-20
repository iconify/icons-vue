<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGinfZMesx"><path class="k5-vjlrin"/><g transform="translate(3 3)" class="jxqi2jbpi"><circle transform="rotate(38.27 11.663 5.118)" class="ankvxfc_w"/><path class="nyi1rb2hl"/><path class="zc46plbst"/><path class="zjzss41qa"/></g></mask></defs><circle mask="url(#SVGinfZMesx)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:microphone-handheld-circle-filled" /></template>
<style>
.ankvxfc_w {
  cx: 11.663px;
  cy: 5.118px;
  r: 3px;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.jxqi2jbpi {
  stroke: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.nyi1rb2hl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m8.544 5.842l-4.562 6.59m7.703-4.112l-5.348 5.97m-2.355-1.858l2.355 1.858");
}

.zc46plbst {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.617 2.867l.821 1.25a5 5 0 0 0 2.483 1.959l1.407.507");
}

.zjzss41qa {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.7 14s-1.034 1.328-1.158 2c-.144.774.135 1.287.514 1.586s1.211.388 1.993.299c2.134-.245 3.423-3.438 5.35-4.385c1.488-.73 1.385-.632 3-1c1.374-.313 2.699-.547 2.699-.547");
}

</style>
