<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yxgtqnbnq"/><path class="pecaz-bmy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:treasury-bill-of-lading" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pecaz-bmy {
  d: path("M18.25 2v2.25h2.25");
}

.yxgtqnbnq {
  d: path("M21.5 11.575v7.675q0 .086-.008.172t-.026.169q-.016.085-.041.167t-.058.162t-.074.155t-.088.147t-.102.138t-.116.127t-.127.116q-.066.054-.138.102q-.071.048-.147.088q-.076.041-.155.074q-.08.033-.162.058t-.167.041t-.169.026q-.086.008-.172.008H4.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058t-.155-.074q-.076-.04-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169q-.008-.086-.008-.172v-9.5q0-.086.008-.172t.026-.169q.016-.085.041-.167t.058-.162q.033-.079.074-.155t.088-.147t.102-.138t.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041t.169-.026T4.25 8h7.4M6 11v7m3.5-7v7m6.5-6.2V21m-2.75-8.5v4m5.5-4v4M14.5 2h3.75l2.25 2.25V9h-6Z");
}

</style>
