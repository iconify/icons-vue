<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q42n4hbgo"/><path class="bq2tyby3j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:status-out-for-delivery" /></template>
<style>
.bq2tyby3j {
  d: path("M12.5 4.5V9H17M3.5 16.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm9.972-1.354q-.141-.153-.309-.273q-.169-.121-.359-.204q-.19-.084-.393-.126q-.204-.043-.411-.043q-.098 0-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132t-.132.145t-.117.158t-.101.168q-.046.087-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194T10 16.5t.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145t.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028t.196.01q.176 0 .349-.031q.173-.03.339-.091q.165-.06.317-.149q.152-.088.286-.202M18.75 21.5S16 19 16 16.75a2.75 2.75 0 0 1 5.5 0c0 2.25-2.75 4.75-2.75 4.75Z");
}

.q42n4hbgo {
  d: path("M13.685 14.5H2.5V6q0-.074.007-.147t.022-.146t.036-.142q.021-.071.049-.139t.063-.133t.076-.126t.087-.119t.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036t.146-.022T4 4.5h8.5L17 9v2.515");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
