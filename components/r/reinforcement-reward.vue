<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr5242fwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reinforcement-reward" /></template>
<style>
.fr5242fwr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.29 3.49l.83 2.07q.29.75 1.09.8l2.22.14q.8.05.18.56L14.9 8.48q-.62.51-.42 1.29l.55 2.15q.2.78-.47.35l-1.88-1.19q-.68-.43-1.36 0l-1.88 1.19q-.67.43-.47-.35l.55-2.15q.2-.78-.42-1.29L7.39 7.06q-.62-.51.18-.56l2.22-.14q.8-.05 1.09-.8l.83-2.07q.29-.74.58 0M4.25 14.75a8 8 0 0 0 15.5 0m-3 .5l3-.5l.75 3");
}

</style>
