<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGKnACQegp)" clip-rule="evenodd" class="ef9ox4jjk"/><defs><linearGradient id="SVGKnACQegp" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="bjfsq2bqn"/><stop offset="1" class="q29knxr1g"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rly" /></template>
<style>
.bjfsq2bqn {
  stop-color: var(--svg-color--ff4500, #ff4500);
}

.ef9ox4jjk {
  fill-rule: evenodd;
  d: path("M19.941 7.5L12 3L4.059 7.5v9l7.94 4.5l7.942-4.5zm-2.648 1.059l-5.294-2.912l-5.295 2.912v5.823l2.647 1.456V10.23l2.647-1.406l2.643 1.404l2.652-1.65z");
}

.ft5dv1b6b {
  fill: none;
}

.q29knxr1g {
  stop-color: var(--svg-color--ffc604, #ffc604);
}

</style>
