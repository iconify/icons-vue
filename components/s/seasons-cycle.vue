<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fj87c9bsl"/><path class="zziqnog_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:seasons-cycle" /></template>
<style>
.fj87c9bsl {
  d: path("M12 4.5a8 8 0 1 0 7 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zziqnog_c {
  d: path("m10 2.5l2 2l-2 2m-1 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
