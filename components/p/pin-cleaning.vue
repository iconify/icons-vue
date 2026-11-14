<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpp3i5b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-cleaning" /></template>
<style>
.lpp3i5b9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.558 19.097l-.058.403h-9L3 9h12l-.834 5.841M3.5 9a5.5 5.5 0 0 1 11 0m2-4.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm3.183 7.739q.067-.008.133-.023q.067-.014.132-.034t.127-.047q.063-.026.123-.057t.117-.069t.111-.079t.103-.088t.094-.098t.086-.106t.075-.113t.065-.119t.054-.124t.042-.13q.018-.065.03-.132t.019-.134T21 10.5q0-.074-.007-.147t-.022-.146t-.036-.142q-.021-.071-.049-.139t-.063-.133t-.076-.126q-.041-.062-.087-.119q-.047-.057-.099-.109t-.109-.099q-.057-.046-.119-.087t-.126-.076q-.065-.035-.133-.063t-.139-.049q-.07-.022-.142-.036q-.073-.015-.146-.022T19.5 9t-.147.007t-.146.022q-.072.014-.142.036q-.071.021-.139.049t-.133.063t-.126.076q-.062.041-.119.087q-.057.047-.109.099t-.099.109t-.087.119t-.076.126t-.063.133t-.049.139t-.036.142q-.015.073-.022.146T18 10.5q0 .113.017.224q.017.112.05.219q.033.108.082.21q.05.101.113.194q.064.093.141.176t.165.152t.186.127q.098.056.203.096M19 22l-2.25-2.75a2.75 2.75 0 1 1 4.5 0Z");
}

</style>
