<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGREiuMecC"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="bcv-gab5w"/><path class="yvvk2dbkw"/><path class="otwdnbb4p"/><path class="y48zmgbtt"/></g></mask></defs><circle mask="url(#SVGREiuMecC)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:sliders-circle-filled" /></template>
<style>
.bcv-gab5w {
  d: path("M5.5 7.75a1 1 0 0 1 1-1H13a1 1 0 1 1 0 2H6.5a1 1 0 0 1-1-1m11.375 0a1 1 0 0 1 1-1H19.5a1 1 0 1 1 0 2h-1.625a1 1 0 0 1-1-1");
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

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

.otwdnbb4p {
  d: path("M15.75 18.75a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5m0 2a2.75 2.75 0 1 0 0-5.5a2.75 2.75 0 0 0 0 5.5m-10.25-8a1 1 0 0 1 1-1h1.625a1 1 0 0 1 0 2H6.5a1 1 0 0 1-1-1m6.5 0a1 1 0 0 1 1-1h6.5a1 1 0 1 1 0 2H13a1 1 0 0 1-1-1");
}

.y48zmgbtt {
  d: path("M10.75 13.75a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5m0 2a2.75 2.75 0 1 0 0-5.5a2.75 2.75 0 0 0 0 5.5");
}

.yvvk2dbkw {
  d: path("M15.75 8.75a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5m0 2a2.75 2.75 0 1 0 0-5.5a2.75 2.75 0 0 0 0 5.5m-10.25 7a1 1 0 0 1 1-1H13a1 1 0 1 1 0 2H6.5a1 1 0 0 1-1-1m11.375 0a1 1 0 0 1 1-1H19.5a1 1 0 1 1 0 2h-1.625a1 1 0 0 1-1-1");
}

</style>
