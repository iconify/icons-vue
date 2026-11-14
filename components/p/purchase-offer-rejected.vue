<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7ltx750x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:purchase-offer-rejected" /></template>
<style>
.l7ltx750x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.043 12H7q-.074 0-.147-.007t-.146-.022q-.072-.014-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076t-.119-.087t-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126t-.063-.133t-.049-.139t-.036-.142q-.015-.073-.022-.146T5.5 10.5V4q0-.074.007-.147t.022-.146q.014-.072.036-.142q.021-.071.049-.139t.063-.133t.076-.126t.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036q.073-.015.146-.022T7 2.5h10q.074 0 .147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109t.087.119t.076.126t.063.133t.049.139t.036.142t.022.146T18.5 4v6.5q0 .074-.007.147t-.022.146t-.036.142q-.021.071-.049.139t-.063.133t-.076.126q-.041.062-.087.119q-.047.057-.099.109t-.109.099q-.057.046-.119.087t-.126.076q-.065.035-.133.063t-.139.049q-.07.022-.142.036q-.073.015-.146.022T17 12h-1.057M12 12v3.1m0 .8v4.2m0 .8v.6M12 5v4.5m3.5 6l5 5m0-5l-5 5");
}

</style>
