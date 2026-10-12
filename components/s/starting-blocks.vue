<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctl9zac6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:starting-blocks" /></template>
<style>
.ctl9zac6s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.9 13.05l-1.2-.9q-.6-.45-1.05.15l-2.7 3.6q-.45.6.15 1.05l1.2.9q.6.45 1.05-.15l2.7-3.6q.45-.6-.15-1.05m9.5-3.5l-1.2-.9q-.6-.45-1.05.15l-2.7 3.6q-.45.6.15 1.05l1.2.9q.6.45 1.05-.15l2.7-3.6q.45-.6-.15-1.05M9 15.5v5.75M18.5 12v9.25m-15.75 0h18.5");
}

</style>
