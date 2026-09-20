<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG7UR1WbPt)" clip-rule="evenodd" class="w647ayupq"/><defs><linearGradient id="SVG7UR1WbPt" x1="3" x2="21" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="uost1iwav"/><stop offset="1" class="c2kirvh2m"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:npro" /></template>
<style>
.c2kirvh2m {
  stop-color: var(--svg-color--1bd6d5, #1bd6d5);
}

.ft5dv1b6b {
  fill: none;
}

.uost1iwav {
  stop-color: var(--svg-color--9498fe, #9498fe);
}

.w647ayupq {
  fill-rule: evenodd;
  d: path("m10.459 3l-6.031 8.601l-.138.569l6.169 8.817l.172-.045l.01-.228l-4.283-6.86l-.267-.659l.381.095l1.38.817l3.063 4.952l.128-.168l-.229-.569l-1.865-3.76l-.085-.38l.228-.103l6.038.057l-.088.426l-2.019 4.101l-.075.342l.131.058l2.976-4.842l.214-.246l1.6-.78l-.049.342l-4.473 7.177l-.009.228l.197.058l6.037-8.599l.138-.572l-6.003-8.658l-.286-.162l-.101.162l.215.424l4.778 7.664l.128.342l-.07.228l-1.76.958l-.346.067l-2.708-6.152l-.478-.805l-.128.122l.089.456l2.032 5.695l.224.912l-6.545.012l-.015-.24l2.373-6.721l-.194-.236l-3.135 6.957l-.396-.043l-1.663-.869l-.176-.227l.074-.342l5.027-8.088l.008-.228z");
}

</style>
