<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v62lmnb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spine" /></template>
<style>
.v62lmnb9q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.42 3.11l4.48-.31q1-.07 1.07.93l.04.49q.07 1-.93 1.07L6.6 5.6q-1 .07-1.07-.93l-.04-.49q-.07-1 .93-1.07m1.79 5.17l4.49-.16q1-.03 1.04.97l.01.5q.04 1-.96 1.03l-4.49.16q-1 .03-1.04-.97l-.01-.5q-.04-1 .96-1.03m.09 4.94l4.49.16q1 .03.96 1.03l-.01.5q-.04 1-1.04.97l-4.49-.16q-1-.03-.96-1.03l.01-.5q.04-1 1.04-.97M6.6 18.4l4.48.31q1 .07.93 1.07l-.04.49q-.07 1-1.07.93l-4.48-.31q-1-.07-.93-1.07l.04-.49q.07-1 1.07-.93m8.65-15.65c1.5 2.75 2 5.75 2 9.25s-.5 6.5-2 9.25");
}

</style>
