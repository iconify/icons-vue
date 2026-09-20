<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m76ok7f1s"/><path class="uo4-ytbux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:med" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m76ok7f1s {
  fill: var(--svg-color--8fb9f4, #8fb9f4);
  d: path("M18.305 6.316c.45-.985 1.271-1.339 2.037-.878c1.052.63.562 1.671.331 2.267l-3.78 10.115c-.433.838-1.192 1.18-1.94.764c-.754-.421-.765-1.36-.45-2.064c1.485-3.336 3.46-9.45 3.802-10.204");
}

.uo4-ytbux {
  fill: var(--svg-color--2073e9, #2073e9);
  d: path("M7.235 6.149c.304-.737 1.238-.99 1.834-.698c.945.467.77 1.3.568 1.89L5.334 18.113c-.411.642-1.17.805-1.727.456c-.68-.427-.664-1.417-.54-1.805c1.305-3.308 3.864-9.867 4.162-10.61zm5.946-.14c.214-.502 1.035-.929 1.609-.563c.703.438.635 1.277.5 1.642l-2.222 5.682c-.365.73-1.074 1.142-1.788.73c-.71-.421-.518-1.287-.338-1.715l2.233-5.777zm6.413 2.053a1.406 1.406 0 1 0 0-2.813a1.406 1.406 0 0 0 0 2.813M15.656 18.75a1.406 1.406 0 1 0 0-2.814a1.406 1.406 0 0 0 0 2.813");
}

</style>
