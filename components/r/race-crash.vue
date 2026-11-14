<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s9qygybjv"/><path class="byojeybyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:race-crash" /></template>
<style>
.byojeybyj {
  d: path("M4.5 10.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m4.098 5.312l.07.163a1.5 1.5 0 0 0 1.167.894l.04.006a.557.557 0 0 1 .385.86l-.125.188a1.5 1.5 0 0 0-.194 1.244l.069.242a.66.66 0 0 1-.635.841h-.254a1.5 1.5 0 0 0-1.06.439l-.186.186a.598.598 0 0 1-.973-.187l-.121-.283a1.5 1.5 0 0 0-.967-.851l-.294-.084a.533.533 0 0 1-.27-.845l.016-.02a1.5 1.5 0 0 0 .271-1.35l-.047-.164a.66.66 0 0 1 .635-.841h.254a1.5 1.5 0 0 0 1.06-.439l.186-.186a.598.598 0 0 1 .973.187");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s9qygybjv {
  d: path("M4.5 10.5h-2V8L5 7h4.5l2-2.5h3L16 7l5.5 1v2.5H19m-10.5 0H15");
}

</style>
