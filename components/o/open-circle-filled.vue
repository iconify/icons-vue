<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGOFcfVXUN"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path class="u4boiyxom"/><path class="mf7ciojof"/><path class="lz7eimbsc"/></g></mask></defs><circle mask="url(#SVGOFcfVXUN)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:open-circle-filled" /></template>
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

.lz7eimbsc {
  d: path("M15 8a1 1 0 1 1 0-2h4a1 1 0 1 1 0 2z");
}

.mf7ciojof {
  d: path("M18 18v-3.5a1 1 0 1 1 2 0V19a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1h4.5a1 1 0 0 1 0 2H8v10zm2-7a1 1 0 1 1-2 0V7a1 1 0 1 1 2 0z");
}

.u4boiyxom {
  d: path("M13.707 13.707a1 1 0 0 1-1.414-1.414l6-6a1 1 0 1 1 1.414 1.414z");
}

</style>
