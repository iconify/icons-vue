<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pd156lb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:org-account" /></template>
<style>
.pd156lb6p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 4.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-6.25 7a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m15.892 2.157q.173-.052.335-.13t.311-.182t.278-.229t.238-.271t.191-.305q.084-.16.14-.331t.086-.35t.029-.359q0-.111-.011-.221t-.032-.218t-.054-.214t-.074-.208q-.043-.102-.095-.2q-.052-.097-.113-.189t-.132-.177q-.07-.086-.148-.164t-.164-.148q-.085-.07-.177-.132q-.092-.061-.189-.113q-.098-.052-.2-.095q-.102-.042-.208-.074t-.214-.054t-.218-.032t-.221-.011t-.221.011t-.218.032q-.108.022-.214.054t-.208.074t-.2.095q-.097.052-.189.113t-.177.132t-.164.148q-.078.078-.148.164q-.07.085-.132.177q-.061.092-.113.189q-.052.098-.095.2q-.042.102-.074.208t-.054.214t-.032.218t-.011.221q0 .155.021.308q.021.154.064.303t.104.291q.062.142.143.274t.179.252t.212.225t.241.193q.127.089.265.159M10.25 6.5l-3 3.25m6.5-3.25l3 3.25m-1 11.75a2 2 0 0 1 0-4a2.5 2.5 0 0 1 4.5.5a1.75 1.75 0 0 1-.25 3.5Z");
}

</style>
