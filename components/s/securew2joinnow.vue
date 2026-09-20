<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="djgp6bbqz"/><circle class="gvqraqbnf"/><path class="qmjjf-9kk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:securew2joinnow" /></template>
<style>
.djgp6bbqz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.099 8.959v3.813a2.311 2.311 0 1 0 4.622 0V8.959m0 3.813v2.311m2.292-3.813a2.31 2.31 0 0 1 2.31-2.311m-2.31 0v6.124M6.71 14.566c.422.355.878.517 1.901.517h.519a1.53 1.53 0 0 0 1.527-1.531A1.53 1.53 0 0 0 9.13 12.02H8.093a1.53 1.53 0 0 1-1.528-1.531a1.53 1.53 0 0 1 1.528-1.531h.518c1.023 0 1.479.162 1.9.516m13.354 4.445a2.311 2.311 0 0 1-4.318-1.147V11.27a2.31 2.31 0 0 1 4.315-1.151m-6.798 3.798a2.311 2.311 0 0 1-4.319-1.145V11.27a2.311 2.311 0 1 1 4.622 0v.75h-4.623m28.388 1.897a2.311 2.311 0 0 1-4.319-1.145V11.27a2.311 2.311 0 1 1 4.622 0v.75h-4.622M20.522 24.014l-2.311 9.244l-2.311-9.244l-2.311 9.244l-2.311-9.244m17.765 3.062a3.064 3.064 0 0 1 6.107-.344c.095.968-.211 1.923-.88 2.51c-1.238 1.087-5.227 4.016-5.227 4.016h6.124");
}

.gvqraqbnf {
  cx: 15.9px;
  cy: 28.636px;
  r: 10.4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qmjjf-9kk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 35.147a10.32 10.32 0 0 0 8.1 3.894c5.743 0 10.4-4.656 10.4-10.4c0-5.754-4.657-10.4-10.4-10.4a10.34 10.34 0 0 0-8.1 3.883");
}

</style>
