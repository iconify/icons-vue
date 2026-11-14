<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldfraeb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:person-dog-walk" /></template>
<style>
.ldfraeb2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 4.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m2.25 5V15l-2 6m2-6l2 6m-2-11l3 1.5l7.241 1.236M14.75 15.5h4v-3H20l1.5 2.25l-1 .75v3h-5.75Zm1 3V21m3.75-2.5V21");
}

</style>
