<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGoxnNLbRh"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="mxzr09thr"/><path class="qmo-83bnc"/></g></mask></defs><circle mask="url(#SVGoxnNLbRh)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:monitor-loop-circle-filled" /></template>
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

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

.mxzr09thr {
  d: path("M4.5 7.5A2.5 2.5 0 0 1 7 5h11.748a2.5 2.5 0 0 1 2.5 2.5v7.651a2.5 2.5 0 0 1-2.5 2.5h-4.874v2.278a1 1 0 1 1-2 0V17.43a1 1 0 0 1 .626-1.78h6.248a.5.5 0 0 0 .5-.5V7.5a.5.5 0 0 0-.5-.5H7a.5.5 0 0 0-.5.5V9a1 1 0 0 1-2 0z");
}

.qmo-83bnc {
  d: path("M8.187 20.59a1 1 0 0 1 1-1h7.374a1 1 0 1 1 0 2H9.187a1 1 0 0 1-1-1m.25-8.208a2.193 2.193 0 1 0-2.058 3.872a2.193 2.193 0 0 0 2.058-3.873m-4.732-.032a4.193 4.193 0 1 1 2.674 6.034l-1.677 3.155a1 1 0 1 1-1.766-.939l1.677-3.155a4.194 4.194 0 0 1-.908-5.095");
}

</style>
