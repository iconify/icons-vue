<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypd6_wrqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:no-food-drink" /></template>
<style>
.ypd6_wrqn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 9.4v11.1m-2-13.1v.1q0 .098.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145q.069.07.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028t.196.01l.072-.001m6.912-.938q.225-.061.458-.061h5.116q.092 0 .183.01q.091.009.181.028q.089.019.177.047q.087.029.17.066t.164.083q.079.046.153.1q.074.053.143.115q.068.061.129.129t.115.142t.1.154t.084.163t.065.171q.029.087.048.177q.019.089.029.18q.009.091.009.183t-.009.183l-.517 4.957M16.578 20.5h-2.751q-.08 0-.16-.007q-.08-.008-.159-.022q-.079-.015-.156-.037t-.152-.051q-.075-.028-.147-.064q-.072-.035-.141-.077t-.132-.091q-.065-.048-.124-.101q-.06-.054-.114-.113t-.104-.123q-.048-.064-.091-.131q-.043-.068-.079-.14t-.066-.146t-.053-.152t-.038-.155q-.016-.079-.024-.159l-.343-3.288M16.5 8.5l1.5-5m-14.5 0l17 17");
}

</style>
