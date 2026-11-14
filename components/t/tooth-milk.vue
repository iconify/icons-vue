<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr5dcmbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tooth-milk" /></template>
<style>
.wr5dcmbfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.982 20.5H7.11q-.081 0-.162-.008q-.082-.007-.162-.022t-.158-.038q-.078-.022-.154-.052t-.149-.066q-.072-.036-.142-.079t-.133-.093q-.065-.049-.125-.104t-.115-.116q-.054-.06-.103-.126q-.048-.065-.091-.134q-.042-.07-.078-.143t-.065-.149q-.028-.077-.05-.155q-.022-.079-.036-.159t-.021-.161l-1.208-14.5q-.008-.09-.006-.181q.002-.09.013-.18q.012-.09.032-.178t.05-.174t.067-.168t.084-.16t.101-.15t.115-.139q.062-.067.129-.127q.068-.06.142-.112t.152-.097t.162-.082q.083-.036.169-.064q.086-.027.175-.046q.088-.018.178-.028q.09-.009.181-.009h9.196q.091 0 .181.009q.09.01.178.028q.089.019.175.046q.086.028.169.064t.162.082q.078.044.152.097q.074.052.142.112t.129.127t.115.139t.101.15t.084.16t.067.168t.05.174t.032.178t.013.18t-.006.181l-.65 7.802M4.5 8.5h12m0 6.5c-1.25 0-1.75 1-1.75 2.25s.75 1.75 1 2.75l.5 1.5l1.5-2l1.5 2l.5-1.5c.25-1 1-1.5 1-2.75S20.25 15 19 15c-.75 0-.75.5-1.25.5s-.5-.5-1.25-.5");
}

</style>
