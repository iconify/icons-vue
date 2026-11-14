<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zau1wqbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vertical-garden" /></template>
<style>
.zau1wqbwr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5h11A3.5 3.5 0 0 1 21 6v12a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 18V6a3.5 3.5 0 0 1 3.5-3.5M3 8.75h18M3 15h18m-9-6.25V5.5m0 3.25L9.5 6M12 8.75L14.5 6M12 15v-3.25M12 15l-2.5-2.75M12 15l2.5-2.75M12 21.5v-3.25m0 3.25l-2.5-2.75M12 21.5l2.5-2.75");
}

</style>
