<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="hu2e-l_if"/><path class="guqyjxwgt"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:stmx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.guqyjxwgt {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.235 4.941h-4S8 9.412 8.705 10.353c.718.956 1.5 1.478.236 3.059C7.06 15.765 4 19.059 4 19.059h4.235s4-4.941 4.47-5.647c.517-.774.898-2.173 0-3.294c-.94-1.177-4.47-5.177-4.47-5.177m11.765 0h-5.177l-2.352 2.824s1.32.405 1.647.47c1.176.236 1.647.236 2.353-.235C16.493 7.986 20 4.941 20 4.941m0 14.118h-5.177l-2.352-2.824s1.32-.405 1.647-.47c1.176-.235 1.647-.235 2.353.235c.022.015 3.529 3.059 3.529 3.059");
}

.hu2e-l_if {
  fill: var(--svg-color--ff2a4d, #ff2a4d);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
