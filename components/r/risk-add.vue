<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibmhywbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:risk-add" /></template>
<style>
.ibmhywbaw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.24 18.5H7.488q-.085 0-.171-.006q-.085-.005-.17-.016t-.168-.028q-.084-.016-.167-.038q-.082-.022-.163-.05q-.081-.027-.16-.06q-.08-.032-.156-.07q-.077-.037-.151-.08q-.074-.042-.146-.09q-.071-.047-.139-.099t-.132-.108t-.125-.116t-.118-.124t-.109-.132q-.052-.067-.1-.138t-.091-.145t-.081-.15t-.072-.155t-.061-.16q-.028-.08-.051-.163q-.023-.082-.04-.166t-.029-.168q-.012-.085-.018-.17t-.007-.171t.004-.171t.015-.17t.027-.169q.015-.084.037-.167q.021-.082.048-.164q.026-.081.058-.16t.069-.156t.079-.152l4.512-8.021q.085-.152.19-.291q.104-.139.226-.263t.259-.23q.138-.107.288-.195t.31-.155t.328-.113q.168-.045.341-.068q.172-.023.346-.023t.346.023t.341.068q.167.046.328.113q.16.067.31.155t.288.195q.137.106.259.23t.226.263t.19.291l3.187 5.665M12 8.5v4m0 2.75h.01M18 15v6m-3-3h6");
}

</style>
