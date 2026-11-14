<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bjicnks1c"/><path class="wp3g1bc6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-pin-off" /></template>
<style>
.bjicnks1c {
  d: path("M14.776 18.708C13.276 20.394 12 21.5 12 21.5S4.5 15 4.5 9.5q0-.512.07-1.019m2.897-4.956q.486-.368 1.025-.654q.538-.285 1.117-.479q.578-.195 1.179-.293Q11.39 2 12 2q.184 0 .368.009t.367.027t.365.045t.363.063t.359.081t.355.098t.35.115t.343.133q.17.07.337.149q.166.079.328.166q.163.086.321.181t.311.197t.301.212t.29.226q.142.117.279.241q.136.124.266.254t.254.266t.241.279q.116.142.226.29t.212.301t.197.311t.181.321q.087.162.166.328q.079.167.149.337q.071.17.133.343t.115.35t.098.355t.081.359t.063.363t.045.365t.027.367t.009.368c0 1.52-.573 3.116-1.401 4.63");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wp3g1bc6v {
  d: path("M14.531 10.576q.219-.515.219-1.076q0-.135-.013-.27q-.013-.134-.04-.266q-.026-.133-.065-.262q-.04-.13-.091-.254q-.052-.125-.116-.244q-.063-.119-.138-.232q-.076-.112-.161-.217q-.086-.104-.181-.2q-.096-.095-.2-.181t-.217-.161t-.232-.138t-.244-.116q-.124-.051-.254-.091q-.129-.039-.262-.065q-.132-.027-.266-.04q-.135-.013-.27-.013q-.535 0-1.031.2M3.5 3.5l17 17");
}

</style>
