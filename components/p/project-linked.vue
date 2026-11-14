<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rbs_qhnvv"/><path class="x6gmtllay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:project-linked" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rbs_qhnvv {
  d: path("M2.5 11.5A1.5 1.5 0 0 1 4 10h2l1.5 1.5H9a1.5 1.5 0 0 1 1.5 1.5v6.5A1.5 1.5 0 0 1 9 21H4a1.5 1.5 0 0 1-1.5-1.5Zm11 0A1.5 1.5 0 0 1 15 10h2l1.5 1.5H20a1.5 1.5 0 0 1 1.5 1.5v6.5A1.5 1.5 0 0 1 20 21h-5a1.5 1.5 0 0 1-1.5-1.5Zm-7.75-8h6a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 11.75 7h-6A1.75 1.75 0 0 1 4 5.25A1.75 1.75 0 0 1 5.75 3.5");
}

.x6gmtllay {
  d: path("M12.5 3.5h5.75A1.75 1.75 0 0 1 20 5.25A1.75 1.75 0 0 1 18.25 7H12.5a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 12.5 3.5");
}

</style>
