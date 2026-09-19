<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldepoek_k"/><path class="c-azqsisl"/><path class="fo9a4lb5g"/><circle class="rydubtb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-discount" /></template>
<style>
.c-azqsisl {
  fill: currentColor;
  d: path("M12.79 21L3 11.21v2c0 .53.21 1.04.59 1.41l7.79 7.79c.78.78 2.05.78 2.83 0l6.21-6.21c.78-.78.78-2.05 0-2.83z");
}

.fo9a4lb5g {
  fill: currentColor;
  d: path("M11.38 17.41c.39.39.9.59 1.41.59s1.02-.2 1.41-.59l6.21-6.21c.78-.78.78-2.05 0-2.83L12.62.58C12.25.21 11.74 0 11.21 0H5C3.9 0 3 .9 3 2v6.21c0 .53.21 1.04.59 1.41zM5 2h6.21L19 9.79L12.79 16L5 8.21z");
}

.ldepoek_k {
  fill: currentColor;
  d: path("M19 9.79L11.21 2H5v6.21L12.79 16zM7.25 5.5a1.25 1.25 0 1 1 0-2.5a1.25 1.25 0 0 1 0 2.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.rydubtb_b {
  cx: 7.25px;
  cy: 4.25px;
  r: 1.25px;
  fill: currentColor;
}

</style>
