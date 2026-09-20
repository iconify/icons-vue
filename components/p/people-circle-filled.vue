<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGFttITchb"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="f9fbot7sa"/><path class="kwq7dhb1q"/><path class="vv3l6ibyv"/><path class="q3frfp1xd"/><path class="n96akebfw"/></g></mask></defs><circle mask="url(#SVGFttITchb)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:people-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.f9fbot7sa {
  d: path("M7 11.25a1 1 0 1 0 0-2a1 1 0 0 0 0 2m0 2a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
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

.kwq7dhb1q {
  d: path("M7.05 14a1.5 1.5 0 0 0-1.5 1.5V17a1 1 0 0 1-2 0v-1.5a3.5 3.5 0 0 1 7 0V17a1 1 0 1 1-2 0v-1.5a1.5 1.5 0 0 0-1.5-1.5M19 11.25a1 1 0 1 1 0-2a1 1 0 0 1 0 2m0 2a3 3 0 1 1 0-6a3 3 0 0 1 0 6");
}

.n96akebfw {
  d: path("M13 14a1 1 0 1 0 0-2a1 1 0 0 0 0 2m0 2a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.q3frfp1xd {
  d: path("M13.05 16.75a2.5 2.5 0 0 0-2.5 2.5v1.5a1 1 0 0 1-2 0v-1.5a4.5 4.5 0 0 1 9 0v1.5a1 1 0 1 1-2 0v-1.5a2.5 2.5 0 0 0-2.5-2.5");
}

.vv3l6ibyv {
  d: path("M18.95 14a1.5 1.5 0 0 1 1.5 1.5V17a1 1 0 1 0 2 0v-1.5a3.5 3.5 0 0 0-7 0V17a1 1 0 1 0 2 0v-1.5a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
