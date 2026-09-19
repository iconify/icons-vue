<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="s-wdh8s9v"/><path class="o38kd7i_w"/><path class="vdczeonpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-airline-seat-individual-suite" /></template>
<style>
.o38kd7i_w {
  fill: currentColor;
  d: path("M19 9h-6v6h8v-4c0-1.1-.9-2-2-2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.s-wdh8s9v {
  cx: 7px;
  cy: 11px;
  r: 1px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

.vdczeonpm {
  fill: currentColor;
  d: path("M7 14c1.66 0 3-1.34 3-3S8.66 8 7 8s-3 1.34-3 3s1.34 3 3 3m0-4c.55 0 1 .45 1 1s-.45 1-1 1s-1-.45-1-1s.45-1 1-1m12-3h-8v8H3V7H1v10h22v-6c0-2.21-1.79-4-4-4m2 8h-8V9h6c1.1 0 2 .9 2 2z");
}

</style>
