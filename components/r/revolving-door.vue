<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="har_fosuv"/><path class="knpqv1ipd"/><path class="pr-xiqbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:revolving-door" /></template>
<style>
.har_fosuv {
  d: path("M13.5 21.5H6.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058q-.079-.033-.155-.074t-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169q-.008-.086-.008-.172V4.25q0-.086.008-.172t.026-.169q.016-.085.041-.167t.058-.162t.074-.155q.04-.076.088-.147q.048-.072.102-.138q.055-.067.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041q.084-.017.169-.026T6.25 2.5h8.5q.086 0 .172.008t.169.026q.085.016.167.041t.162.058q.079.033.155.074t.147.088t.138.102t.127.116q.061.06.116.127q.054.066.102.138q.048.071.088.147q.041.076.074.155q.033.08.058.162t.041.167t.026.169q.008.086.008.172v6.425M7.5 9l3-3m-3 6.5l6-6m0 4.5v2.9m6 1.252A3 3 0 0 1 18 20.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.knpqv1ipd {
  d: path("M16.5 20.348A3 3 0 0 1 18 14.75");
}

.pr-xiqbis {
  d: path("M16.75 13.5L18 14.75L16.75 16m2.5 3.5L18 20.75L19.25 22");
}

</style>
