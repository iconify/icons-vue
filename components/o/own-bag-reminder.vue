<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kt4a_fh2n"/><path class="bcqvwl-4v"/><path class="hymbdsbrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:own-bag-reminder" /></template>
<style>
.bcqvwl-4v {
  d: path("M4 10c0-7 6.5-7 6.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hymbdsbrg {
  d: path("M8.5 10c0-7 6.5-7 6.5 0M2.5 15h9.7m2.05 3a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0M18 16v2m0 2h.01");
}

.kt4a_fh2n {
  d: path("M12.5 21.5H4.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058t-.155-.074q-.076-.04-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169q-.008-.086-.008-.172v-8q0-.086.008-.172t.026-.169q.016-.085.041-.167t.058-.162q.033-.079.074-.155t.088-.147t.102-.138t.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041t.169-.026T4.25 10h10.5q.08 0 .16.007q.08.008.16.022q.079.015.156.037t.152.051t.147.064t.141.078t.133.09t.124.102q.059.054.114.113q.054.059.103.123t.092.132t.079.14t.066.146t.052.152t.038.156t.024.159");
}

</style>
