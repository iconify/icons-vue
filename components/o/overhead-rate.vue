<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="segd6kb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:overhead-rate" /></template>
<style>
.segd6kb8l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 6a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m11.812 8.399q.188-.43.188-.899q0-.111-.011-.221t-.032-.218t-.054-.214t-.074-.208q-.043-.102-.095-.2q-.052-.097-.113-.189t-.132-.177q-.07-.086-.148-.164t-.164-.148t-.177-.132t-.189-.113t-.2-.095q-.102-.042-.208-.074t-.214-.054t-.218-.032t-.221-.011t-.221.011t-.218.032q-.108.022-.214.054t-.208.074t-.2.095q-.097.052-.189.113t-.177.132q-.086.07-.164.148t-.148.164t-.132.177t-.113.189t-.095.2q-.042.102-.074.208t-.054.214t-.032.218t-.011.221t.011.221t.032.218q.022.108.054.214t.074.208t.095.2q.052.097.113.189t.132.177q.07.086.148.164t.164.148t.177.132t.189.113t.2.095q.102.042.208.074t.214.054t.218.032t.221.011q.384 0 .747-.128M4 15.5L15.5 4m.736 13.554l1.5-1.375a1.5 1.5 0 0 1 2.028 0l1.5 1.375a1.5 1.5 0 0 1 .486 1.106v1.59a1.5 1.5 0 0 1-1.5 1.5h-3a1.5 1.5 0 0 1-1.5-1.5v-1.59a1.5 1.5 0 0 1 .486-1.106");
}

</style>
