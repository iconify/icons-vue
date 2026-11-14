<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxfjfu3pr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:valve-actuator" /></template>
<style>
.pxfjfu3pr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.671 12.585l5.658 2.83a1.5 1.5 0 0 0 1.342 0l5.658-2.83a1.5 1.5 0 0 1 2.171 1.342v3.646a1.5 1.5 0 0 1-2.171 1.342l-5.658-2.83a1.5 1.5 0 0 0-1.342 0l-5.658 2.83A1.5 1.5 0 0 1 3.5 17.573v-3.646a1.5 1.5 0 0 1 2.171-1.342M12 9v6.75M10.125 3h3.75A2.625 2.625 0 0 1 16.5 5.625v.75A2.625 2.625 0 0 1 13.875 9h-3.75A2.625 2.625 0 0 1 7.5 6.375v-.75A2.625 2.625 0 0 1 10.125 3");
}

</style>
