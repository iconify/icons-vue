<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="qe-_elbpx"/><path clip-rule="evenodd" class="vwl8yybtg"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ssx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qe-_elbpx {
  fill: var(--svg-color--f23a2e, #f23a2e);
  d: path("M24 0H0v24h24z");
}

.vwl8yybtg {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M4 19.467c0-.088 1.345-4.034 2.017-5.997c.224.383 1.092 1.012 2.78 1.09a.27.27 0 0 0 .213.107h4.045a.8.8 0 1 0 0-.534H9.01a.27.27 0 0 0-.235.14c-1.537-.048-3.956-1.008-3.654-5.008c.218-2.886 3.224-4.732 4.755-4.732H20l-2.096 6.089c-.573-.811-2.026-1.155-2.86-1.23a.27.27 0 0 0-.168-.059h-4.045a.8.8 0 1 0 0 .534h4.045a.26.26 0 0 0 .175-.066c1.837.202 3.785 1.176 3.785 4.59c0 3.543-3.076 4.86-4.615 5.076z");
}

</style>
