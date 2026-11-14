<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ocxs56bja"/><path class="s33p-witw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tenant-portal" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ocxs56bja {
  d: path("M6 3.5h12A3.5 3.5 0 0 1 21.5 7v10a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 17V7A3.5 3.5 0 0 1 6 3.5m-3.5 4h19m-16.25-2h.01m2.49 0h.01");
}

.s33p-witw {
  d: path("m8.512 13.552l2.5-2.188a1.5 1.5 0 0 1 1.976 0l2.5 2.188A1.5 1.5 0 0 1 16 14.681V16.5a1.5 1.5 0 0 1-1.5 1.5h-5A1.5 1.5 0 0 1 8 16.5v-1.819a1.5 1.5 0 0 1 .512-1.129");
}

</style>
