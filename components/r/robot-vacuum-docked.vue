<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yts0-uxol"/><path class="gq3f9i3sh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:robot-vacuum-docked" /></template>
<style>
.gq3f9i3sh {
  d: path("M3 6.5v3a9 3.5 0 0 0 18 0v-3m-7.2 13.25H4.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058t-.155-.074q-.076-.04-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169Q2.5 18.086 2.5 18t.008-.172t.026-.169q.016-.085.041-.167t.058-.162t.074-.155t.088-.147t.102-.138t.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041t.169-.026q.086-.008.172-.008h9.7m4.532-1.041l-2.177 2.585a.582.582 0 0 0 .445.956a.858.858 0 0 1 .801 1.167l-.176.458a.296.296 0 0 0 .503.298l2.312-2.721a.578.578 0 0 0-.44-.952a.9.9 0 0 1-.855-1.186L19 15.5a.303.303 0 0 0-.518-.291");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yts0-uxol {
  d: path("M3 6.5a9 3.5 0 1 0 18 0a9 3.5 0 1 0-18 0");
}

</style>
