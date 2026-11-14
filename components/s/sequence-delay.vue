<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="br_7oubdy"/><path class="sbezkcbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sequence-delay" /></template>
<style>
.br_7oubdy {
  d: path("M4.25 2.5h6A1.75 1.75 0 0 1 12 4.25A1.75 1.75 0 0 1 10.25 6h-6A1.75 1.75 0 0 1 2.5 4.25A1.75 1.75 0 0 1 4.25 2.5m2.5 6.25h6a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-6A1.75 1.75 0 0 1 5 10.5a1.75 1.75 0 0 1 1.75-1.75m7.55 9.75H9.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058q-.079-.033-.155-.074t-.147-.088t-.138-.102t-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169q-.008-.086-.008-.172t.008-.172q.009-.085.026-.169q.016-.085.041-.167t.058-.162t.074-.155t.088-.147t.102-.138t.116-.127t.127-.116t.138-.102t.147-.088t.155-.074t.162-.058t.167-.041t.169-.026T9.25 15h3.5m2.75-.25h5m-5 6.5h5m-4-6.5v1l3 4.5v1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sbezkcbzn {
  d: path("M19.5 14.75v1l-3 4.5v1");
}

</style>
