<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ik8rskbqq"/><path class="g8dfuzbgj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:usdv-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g8dfuzbgj {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.004 4.47a.235.235 0 1 0 0-.47a.235.235 0 0 0 0 .47m-8 7.53a8 8 0 0 1 7.059-7.944v.236a7.765 7.765 0 0 0 0 15.416v.236A8 8 0 0 1 4.003 12m15.765 0a7.765 7.765 0 0 1-6.824 7.708v.236a8 8 0 0 0 0-15.888v.236A7.765 7.765 0 0 1 19.77 12m-7.53 7.765a.236.236 0 1 1-.471 0a.236.236 0 0 1 .471 0M10.06 9.176H7.914a.094.094 0 0 0-.084.132l.597 1.28h2.32l-.602-1.355a.09.09 0 0 0-.085-.057M8.865 11.53l-.216-.47h2.306l.211.47zm.221.471h2.292l.541 1.219c.033.075.141.075.17 0l1.774-3.986a.09.09 0 0 1 .085-.057h2.145a.095.095 0 0 1 .093.087a.1.1 0 0 1-.008.045l-3.21 6.87a.09.09 0 0 1-.085.056h-1.76a.1.1 0 0 1-.084-.055z");
}

.ik8rskbqq {
  fill: var(--svg-color--5554ed, #5554ed);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
