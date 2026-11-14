<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avgv-rjkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:master-bedroom" /></template>
<style>
.avgv-rjkd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5V21m0-4h9.2m-9.2-5H19q.169 0 .337.023q.167.023.33.068t.318.111t.301.154t.277.193t.248.228t.216.26t.178.286M7 8h.5a2 2 0 0 1 2 2a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2a2 2 0 0 1 2-2m7.5 12v-3.404a.465.465 0 0 1 .875-.221a.958.958 0 0 0 1.7-.026l.05-.099a.978.978 0 0 1 1.75 0l.05.099a.958.958 0 0 0 1.7.026a.465.465 0 0 1 .875.221V20a1.5 1.5 0 0 1-1.5 1.5h-4a1.5 1.5 0 0 1-1.5-1.5");
}

</style>
