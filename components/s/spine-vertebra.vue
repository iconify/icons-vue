<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkg4xzywc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spine-vertebra" /></template>
<style>
.jkg4xzywc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 2.75h11.5q1 0 .42.81l-.34.48q-.58.81.01 1.62l.32.43q.59.81-.41.81H6.25q-1 0-.41-.81l.32-.43q.59-.81.01-1.62l-.34-.48q-.58-.81.42-.81m0 7.15h11.5q1 0 .42.81l-.34.48q-.58.81 0 1.62l.34.48q.58.81-.42.81H6.25q-1 0-.42-.81l.34-.48q.58-.81 0-1.62l-.34-.48q-.58-.81.42-.81m0 7.2h11.5q1 0 .41.81l-.32.43q-.59.81-.01 1.62l.34.48q.58.81-.42.81H6.25q-1 0-.42-.81l.34-.48q.58-.81-.01-1.62l-.32-.43q-.59-.81.41-.81");
}

</style>
