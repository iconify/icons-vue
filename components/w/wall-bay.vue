<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bt4y1hbli"/><path class="ibax_6bol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wall-bay" /></template>
<style>
.bt4y1hbli {
  d: path("M4.5 6h15v13h-15Zm-1-3.5h17V6h-17Zm1 16.5h15v2.5h-15Zm-2-7h19m-19 7h19");
}

.ibax_6bol {
  d: path("M6.5 8h4v4h-4ZM13 9h4.5v3H13Zm-5.5 5.5H11V19H7.5Zm5.5 1h4.5V19H13Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
