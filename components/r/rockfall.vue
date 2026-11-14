<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi-pkyf9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rockfall" /></template>
<style>
.wi-pkyf9v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 5.5l16.5 15h2.5M12.698 6.309l.14-.839a1.5 1.5 0 0 1 1.116-1.209l1.807-.451a1.5 1.5 0 0 1 1.742.864l.406.947a1.5 1.5 0 0 1-.788 1.97l-1.55.664a1.5 1.5 0 0 1-1.148.014l-.802-.321a1.5 1.5 0 0 1-.923-1.639m6.722 4.454l.08-.013a1.486 1.486 0 0 1 1.715 1.255l.108.756a1.5 1.5 0 0 1-1.011 1.635L20 14.5a1.296 1.296 0 0 1-1.696-1.069l-.125-1.002a1.5 1.5 0 0 1 1.241-1.666");
}

</style>
