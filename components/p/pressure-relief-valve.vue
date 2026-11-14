<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aov8d5-nv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pressure-relief-valve" /></template>
<style>
.aov8d5-nv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21v-3a3 3 0 0 1 3-3h1.5m2.625-3h1.75a2.625 2.625 0 0 1 2.625 2.625v.75A2.625 2.625 0 0 1 12.875 18h-1.75A2.625 2.625 0 0 1 8.5 15.375v-.75A2.625 2.625 0 0 1 11.125 12m4.375 3h5M12 11.5za.81.81 0 0 0-.447-.724L11 10.5a.488.488 0 0 1 .047-.893L12 9.25a.801.801 0 0 0 0-1.5l-.953-.357A.488.488 0 0 1 11 6.5l.665-.332A.61.61 0 0 0 12 5.625zM8.5 5.25a3.5 2.75 0 0 1 7 0Z");
}

</style>
