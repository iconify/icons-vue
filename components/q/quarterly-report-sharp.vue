<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pn1vbwbte"/><path class="djendxb_n"/><path class="s_i5fqbbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:quarterly-report-sharp" /></template>
<style>
.djendxb_n {
  d: path("M12 9.75A4.25 4.25 0 1 0 16.25 14");
}

.pn1vbwbte {
  d: path("M4.25 2.75h15.5v18.5H4.25zm4.25 3.5h7");
}

.s_i5fqbbk {
  d: path("M12.75 13.25v-3.5h3.5v3.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
