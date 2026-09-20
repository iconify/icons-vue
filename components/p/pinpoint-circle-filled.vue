<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGNp6oZdpM"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="xsvnywbmy"/><path class="d_e2q_brs"/></g></mask></defs><circle mask="url(#SVGNp6oZdpM)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:pinpoint-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.d_e2q_brs {
  d: path("M5.5 11.123C5.5 15.366 9.882 22.5 13 22.5s7.5-7.134 7.5-11.377C20.5 6.917 17.146 3.5 13 3.5s-7.5 3.417-7.5 7.623m13 0c0 3.28-3.745 9.377-5.5 9.377s-5.5-6.097-5.5-9.377C7.5 8.013 9.967 5.5 13 5.5s5.5 2.513 5.5 5.623");
}

.ft5dv1b6b {
  fill: none;
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

.xsvnywbmy {
  d: path("M13 14.5a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7m0-5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3");
}

</style>
