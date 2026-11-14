<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q64nvkbxy"/><path class="iahexwbka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:outlet-village" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iahexwbka {
  d: path("M6 21.5v-5h3v5M15 10h3m-3.25 11.25l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

.q64nvkbxy {
  d: path("M11.916 21.188q-.197.152-.432.232q-.236.08-.484.08H4q-.074 0-.147-.007t-.146-.022t-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076t-.119-.087q-.057-.047-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126q-.035-.065-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T2.5 20v-7.879q0-.148.029-.292q.029-.145.085-.282t.139-.259q.082-.123.186-.227l3.5-3.5q.052-.052.109-.099t.118-.088q.062-.041.127-.075q.065-.035.133-.063q.068-.029.138-.05t.143-.036t.146-.021q.073-.008.147-.008t.147.008t.146.021q.072.015.143.036t.138.05q.068.028.133.063q.065.034.127.075q.061.041.118.088t.109.099l3.5 3.5q.104.104.186.227t.139.259q.056.137.085.282t.029.292v7.505m0-9.626l4-4.5L21 10v1.915");
}

</style>
