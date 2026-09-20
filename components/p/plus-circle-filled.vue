<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGou9pwcLW"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path class="i_lialbjv"/><path class="a_fwwub7q"/></g></mask></defs><circle mask="url(#SVGou9pwcLW)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:plus-circle-filled" /></template>
<style>
.a_fwwub7q {
  d: path("M12 8a1 1 0 0 1 2 0v10a1 1 0 1 1-2 0z");
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

.i_lialbjv {
  d: path("M8 14a1 1 0 1 1 0-2h10a1 1 0 1 1 0 2z");
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

</style>
