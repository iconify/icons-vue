<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="epd7h5bdl"/><path class="ay4x2wi-v"/><path class="seo644t7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:side-conversation" /></template>
<style>
.ay4x2wi-v {
  d: path("M15 12v5.5a2 2 0 0 0 2 2h4.5");
}

.epd7h5bdl {
  d: path("M12.157 14.5H9.5L6 18v-3.5H4.5q-.098 0-.196-.01q-.098-.009-.194-.028q-.097-.02-.191-.048q-.094-.029-.184-.066q-.091-.038-.178-.084q-.086-.046-.168-.101t-.158-.117t-.145-.132t-.132-.145t-.117-.158t-.101-.168q-.046-.087-.084-.178q-.037-.09-.066-.184q-.028-.094-.048-.191q-.019-.096-.028-.194T2.5 12.5v-8q0-.098.01-.196q.009-.098.028-.194q.02-.097.048-.191q.029-.094.066-.184q.038-.091.084-.178q.046-.086.101-.168t.117-.158t.132-.145t.145-.132t.158-.117t.168-.101q.087-.046.178-.084q.09-.037.184-.066q.094-.028.191-.048q.096-.019.194-.028T4.5 2.5h13q.098 0 .196.01q.098.009.194.028q.097.02.191.048q.094.029.184.066q.091.038.178.084q.086.046.168.101t.158.117t.145.132t.132.145t.117.158t.101.168q.046.087.084.178q.037.09.066.184q.028.094.048.191q.019.096.028.194t.01.196v8q0 .09-.008.18q-.008.089-.024.178q-.016.088-.04.175t-.056.171t-.071.165t-.085.159t-.099.15t-.113.14t-.124.13t-.136.118t-.146.105t-.154.092t-.162.078t-.169.063q-.085.027-.173.047t-.177.032");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.seo644t7l {
  d: path("m19.25 17.25l2.25 2.25l-2.25 2.25");
}

</style>
