<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wpy3tjb0j"/><path class="zkfth4bpl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:remit-beneficiary-info" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wpy3tjb0j {
  d: path("M12.6 19.5H2.5v-15h19v7.1");
}

.zkfth4bpl {
  d: path("M6 9.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM4.75 16C5 14.5 6.4 13.5 8 13.5s3 1 3.25 2.5M14 9h4.5M14 12h3m4 3l-5.25 5.25m-.25-4v4.25h4.25");
}

</style>
