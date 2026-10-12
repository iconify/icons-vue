<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb0sqob-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:meadow" /></template>
<style>
.yb0sqob-t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25h18.5M8 21.25V12m8 9.25V9.75M4.25 21.25l-1-3.75m8.5 3.75l1-4m7.25 4l1-3.75m-5-1c1.25-2 2.75-2.75 4.5-2.5c-.5 1.75-2 2.75-4.5 2.5M8.3 7.02l.2.33q.3.51.9.52h.38q.6.01.31.53l-.19.33q-.3.52 0 1.04l.19.33q.29.53-.31.53H9.4q-.6.01-.9.52l-.2.33q-.3.52-.6 0l-.2-.33q-.3-.51-.9-.52h-.38q-.6 0-.31-.53l.19-.33q.3-.52 0-1.04l-.19-.33q-.29-.52.31-.53h.38q.6-.01.9-.52l.2-.33q.3-.52.6 0m8.04-3.16l.24.43q.35.61 1.04.6l.49-.01q.7 0 .35.6l-.25.42q-.36.6 0 1.2l.25.42q.35.61-.35.6l-.49-.01q-.69-.01-1.04.6l-.24.43q-.34.61-.68 0l-.24-.43q-.34-.61-1.04-.6l-.49.01q-.7.01-.35-.6l.25-.42q.36-.6 0-1.2l-.25-.42q-.35-.6.35-.6l.49.01q.69.01 1.04-.6l.24-.43q.34-.61.68 0");
}

</style>
