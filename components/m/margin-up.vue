<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6qp4kbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:margin-up" /></template>
<style>
.o6qp4kbtv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 16.5l13-13m-12.25 3a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm11.152 8.203q.17-.27.259-.577t.089-.626q0-.111-.011-.221t-.032-.218t-.054-.214t-.074-.208q-.043-.102-.095-.2q-.052-.097-.113-.189t-.132-.177q-.07-.086-.148-.164t-.164-.148t-.177-.132t-.189-.113t-.2-.095q-.102-.042-.208-.074t-.214-.054t-.218-.032t-.221-.011t-.221.011t-.218.032q-.108.022-.214.054t-.208.074t-.2.095q-.097.052-.189.113t-.177.132q-.086.07-.164.148t-.148.164t-.132.177t-.113.189t-.095.2q-.042.102-.074.208t-.054.214t-.032.218t-.011.221t.011.221t.032.218q.022.108.054.214t.074.208t.095.2q.052.097.113.189t.132.177q.07.086.148.164t.164.148t.177.132t.189.113t.2.095q.102.042.208.074t.214.054t.218.032t.221.011q.306 0 .601-.082q.294-.081.556-.239M18.5 21.5v-6m-2.75 2.75l2.75-2.75l2.75 2.75");
}

</style>
