<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGfxg4jenS"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="ktwznfblf"/></mask></defs><circle mask="url(#SVGfxg4jenS)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:triangle-left-circle-filled" /></template>
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

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.ktwznfblf {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M10.002 13L17 17.037V8.963zm-2.5-.866a1 1 0 0 0 0 1.732l9.998 5.769a1 1 0 0 0 1.5-.866V7.23a1 1 0 0 0-1.5-.866z");
}

</style>
