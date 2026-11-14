<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_k4y97cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:transfer-tax" /></template>
<style>
.c_k4y97cs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 2.5h11.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 17.75 6H6.25A1.75 1.75 0 0 1 4.5 4.25A1.75 1.75 0 0 1 6.25 2.5M6 6v12M18 6v8.1m-5.8 7.4H6.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058q-.079-.033-.155-.074t-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169q-.008-.086-.008-.172t.008-.172q.009-.085.026-.169q.016-.085.041-.167t.058-.162t.074-.155t.088-.147t.102-.138t.116-.127t.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041q.084-.017.169-.026T6.25 18h7.8M9 10h6m-6 3.5h4m2 7.5l6-6m-5.5.5h.01m4.99 5h.01");
}

</style>
