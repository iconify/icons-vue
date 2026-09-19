<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c7l37fd-d"/><path class="v5qh9ofbq"/><path class="qddn30dqu"/><path class="pxlbyf0dk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:truemoney-biz-connect" /></template>
<style>
.c7l37fd-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.008 38.099c-1.599 1.449-4.175 2.385-7.091 2.385h-3.62c-4.874 0-8.797-2.615-8.797-5.864V13.38c0-3.249 3.923-5.864 8.796-5.864h3.62c2.917 0 5.493.936 7.092 2.385");
}

.pxlbyf0dk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.532 35.059c.206.908.862 1.554 2.505 1.554c2.09 0 2.583-1.047 2.583-2.346v-6.689h7.88v7.042c0 3.249-3.923 5.864-8.796 5.864h-3.62c-4.874 0-8.797-2.615-8.797-5.864V13.38c0-3.249 3.923-5.864 8.796-5.864h3.62c4.874 0 8.797 2.615 8.797 5.864v6.391h-7.88v-6.053c0-1.3-.494-2.346-2.583-2.346c-1.636 0-2.294.64-2.502 1.542");
}

.qddn30dqu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.745 35.059c.205.908.862 1.554 2.504 1.554c2.09 0 2.584-1.047 2.584-2.346v-6.581a2.926 2.926 0 0 0-2.92-2.932h-2.192m.026-11.84c.21-.901.867-1.542 2.502-1.542c2.09 0 2.584 1.046 2.584 2.346v4.762a2.926 2.926 0 0 1-2.92 2.932h-2.192M36.935 40.27c-3.714-.686-6.426-2.949-6.426-5.65V13.38c0-2.701 2.712-4.964 6.426-5.65");
}

.v5qh9ofbq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.148 40.27c-3.715-.686-6.426-2.949-6.426-5.65V13.38c0-2.701 2.711-4.964 6.426-5.65");
}

</style>
