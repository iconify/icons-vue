<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="r85q1cc1k"/><path clip-rule="evenodd" class="rxh9wkmpp"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sender-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r85q1cc1k {
  fill: var(--svg-color--2e79df, #2e79df);
  d: path("M24 0H0v24h24z");
}

.rxh9wkmpp {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M14.498 10.628q.354.13.644.34a2.2 2.2 0 0 1 .817 1.14q.071.234.091.482c.098 1.16-.61 2.508-1.87 3.51l-.057.044q-.33.256-.705.476L7.645 20a4.18 4.18 0 0 1 .858-3.203c.309-.39.692-.729 1.145-.994l3.372-1.974a1.75 1.75 0 0 0 .839-1.208a1.74 1.74 0 0 0-.201-1.17a1.705 1.705 0 0 0-1.732-.849l.061-.028q.46-.114.902-.146c.586-.043 1.136.025 1.609.2M16.355 4a4.18 4.18 0 0 1-.857 3.203a4.1 4.1 0 0 1-1.146.994L10.98 10.17a1.75 1.75 0 0 0-.839 1.208c-.069.389-.008.803.201 1.17a1.71 1.71 0 0 0 1.732.849l-.061.028a5.3 5.3 0 0 1-.902.146c-.586.043-1.136-.025-1.609-.2a2.7 2.7 0 0 1-.643-.34a2.2 2.2 0 0 1-.91-1.622c-.097-1.16.611-2.508 1.872-3.51l.057-.044q.329-.256.704-.476z");
}

</style>
