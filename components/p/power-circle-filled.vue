<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGRxGMhejW"><path class="k5-vjlrin"/><g transform="translate(3 3)" class="ivjvz2eii"><path class="qi4azoban"/><rect class="t9nly_bze"/></g></mask></defs><circle mask="url(#SVGRxGMhejW)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:power-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.qi4azoban {
  d: path("M4.338 5.179a1 1 0 1 1 1.424 1.404A6.13 6.13 0 0 0 4 10.901C4 14.272 6.69 17 10 17s6-2.728 6-6.1c0-1.643-.641-3.18-1.762-4.317a1 1 0 1 1 1.424-1.404A8.13 8.13 0 0 1 18 10.9c0 4.47-3.578 8.1-8 8.1c-4.421 0-8-3.63-8-8.1c0-2.173.85-4.213 2.338-5.721");
}

.t9nly_bze {
  width: 2px;
  height: 10.5px;
  x: 9px;
  y: 1px;
  rx: 1px;
}

</style>
