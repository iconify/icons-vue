<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bi1bxkyxr"/><circle class="srqzxr9-m"/><path class="de6e2wbih"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sunflower" /></template>
<style>
.bi1bxkyxr {
  d: path("m12.25 3.3l.53 1.17q.24.55.7.16l.99-.83q.46-.38.44.22l-.03 1.28q-.01.6.57.46l1.25-.32q.58-.15.3.39l-.58 1.14q-.28.53.31.65l1.26.26q.59.12.11.48l-1.02.78q-.48.36 0 .72l1.02.78q.48.36-.11.48l-1.26.26q-.59.12-.31.65l.58 1.14q.28.54-.3.39l-1.25-.32q-.58-.14-.57.46l.03 1.28q.02.6-.44.22l-.99-.83q-.46-.39-.7.16l-.53 1.17q-.25.55-.5 0l-.53-1.17q-.24-.55-.7-.16l-.99.83q-.46.38-.44-.22l.03-1.28q.01-.6-.57-.46l-1.25.32q-.58.15-.3-.39l.58-1.14q.28-.53-.31-.65l-1.26-.26q-.59-.12-.11-.48l1.02-.78q.48-.36 0-.72L5.9 8.36q-.48-.36.11-.48l1.26-.26q.59-.12.31-.65L7 5.83q-.28-.54.3-.39l1.25.32q.58.14.57-.46l-.03-1.28q-.02-.6.44-.22l.99.83q.46.39.7-.16l.53-1.17q.25-.55.5 0");
}

.de6e2wbih {
  d: path("M12 16.25v5M12 20c.5-1.75 2.25-2.75 4.5-2.75C16 19 14.25 20 12 20");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.srqzxr9-m {
  cx: 12px;
  cy: 9.5px;
  r: 2.75px;
}

</style>
