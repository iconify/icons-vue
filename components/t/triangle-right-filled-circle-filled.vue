<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGMOmoucTs"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="kax-q9blx"/><path class="hsit5q6hy"/></g></mask></defs><circle mask="url(#SVGMOmoucTs)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:triangle-right-filled-circle-filled" /></template>
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

.hsit5q6hy {
  d: path("M8.5 19.635a1 1 0 0 1-1.5-.866V7.23a1 1 0 0 1 1.5-.866l9.999 5.769a1 1 0 0 1 0 1.732zM13.997 13L10 10.694v4.612z");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.kax-q9blx {
  d: path("M18.499 12.134a1 1 0 0 1 0 1.732l-10 5.769A1 1 0 0 1 7 18.769V7.23a1 1 0 0 1 1.5-.866z");
}

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

</style>
