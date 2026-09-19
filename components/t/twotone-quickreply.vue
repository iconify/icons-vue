<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-1vv8bbi"/><path class="u2rgr256h"/><path class="qolfhjb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-quickreply" /></template>
<style>
.d-1vv8bbi {
  fill: currentColor;
  d: path("M4 4v13.17L5.17 16H15v-6h5V4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.qolfhjb7t {
  fill: currentColor;
  d: path("m19 23l3.5-7h-2.2l1.7-4h-5v6h2z");
}

.u2rgr256h {
  fill: currentColor;
  d: path("M5.17 16L4 17.17V4h16v6h2V4c0-1.1-.9-2-2-2H4c-1.1 0-1.99.9-1.99 2L2 22l4-4h9v-2z");
}

</style>
