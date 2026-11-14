<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ghdc585me"/><path class="bsmnuu7uq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pipeline-leak" /></template>
<style>
.bsmnuu7uq {
  d: path("M15.34 13.491q-.069-.007-.136-.02t-.133-.034q-.066-.019-.13-.045q-.063-.025-.124-.057q-.062-.031-.12-.068q-.058-.036-.112-.078t-.105-.089t-.096-.098t-.087-.106t-.077-.113t-.066-.121q-.03-.061-.055-.125q-.024-.064-.043-.13q-.018-.067-.031-.134q-.012-.068-.019-.136T14 12V6q0-.074.007-.147t.022-.146q.014-.072.036-.142q.021-.071.049-.139t.063-.133t.076-.126t.087-.119t.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036q.073-.015.146-.022T15.5 4.5t.147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076t.119.087q.057.047.109.099t.099.109t.087.119t.076.126t.063.133t.049.139t.036.142q.015.073.022.146T17 6v5.879M9 15.75l1.75 3a2 2 0 1 1-3.5 0Zm9-1.25V18m0 3h.01");
}

.ghdc585me {
  d: path("M2.5 6.5H14m3 0h4.5m-19 5H8L9 13l1-1.5h4m3 0h4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
