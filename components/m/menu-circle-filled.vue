<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGfhEiufEz"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="b5vqnzb1n"/></mask></defs><circle mask="url(#SVGfhEiufEz)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:menu-circle-filled" /></template>
<style>
.b5vqnzb1n {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M5 11a1 1 0 0 1 1-1h10.308a1 1 0 1 1 0 2H6a1 1 0 0 1-1-1m0-4a1 1 0 0 1 1-1h14a1 1 0 1 1 0 2H6a1 1 0 0 1-1-1m0 8a1 1 0 0 1 1-1h14a1 1 0 1 1 0 2H6a1 1 0 0 1-1-1m0 4a1 1 0 0 1 1-1h10.308a1 1 0 1 1 0 2H6a1 1 0 0 1-1-1");
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

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

</style>
