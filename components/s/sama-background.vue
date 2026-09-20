<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="qhhkes77v"/><path class="k186noc7r"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sama-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k186noc7r {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.999 4.001c-1.21 0-3.1.61-3.88 1.175V4.94c-.485.395-1.5 1.27-1.7 1.65v-.47c-.4.39-1.21 1.454-1.21 2.584l-.24-.235a2.44 2.44 0 0 0-.244 2.59l-.485-.47c-.16.86-.335 2.775.245 3.53l-.245-.24c-.08.24-.145.8.245 1.18L4 14.823c.325.86 1.165 2.635 1.94 2.82h-.485c.24.235.825.71 1.21.71l-.24.235c.97.47 3.49 1.41 5.814 1.41c2.33 0 4.53-.94 5.334-1.41h-.24c.32-.16 1.015-.565 1.21-.945h-.485c.485-.31 1.55-1.315 1.94-2.82l-.485.235c.08-.08.245-.38.245-.94l-.485.236a3.1 3.1 0 0 0 .725-2.12c0-1.13-.16-1.57-.24-1.65l-.245.475c.08-.63.1-2.025-.485-2.59v.47c-.16-.785-.68-2.45-1.45-2.82v.236c-.085-.315-.54-1.035-1.7-1.415v.235c-.73-.39-2.52-1.175-3.88-1.175m-5 9.749c.086-.085.35-.25.75-.25c.5 0 1.75.25 1.75 1.25c0 .25-.15.75-.75.75C8 15.5 8 15 8 14.75c0-.126.065-.25.125-.376c.065-.125.125-.25.125-.375c0-.25-.75-.474-1.25-.25m5 5.249c-.665-.44-2-1.445-2-1.97c0-.655 1.11-1.53 2-1.53s2 .875 2 1.53c0 .5-1.265 1.43-1.9 1.9zm4.75-5.5c.4 0 .664.166.749.25c-.735-.25-1.25 0-1.25.25c0 .125.065.25.125.375c.065.125.125.25.125.375c0 .25 0 .75-.75.75c-.6 0-.75-.5-.75-.75c0-1 1.25-1.25 1.75-1.25");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qhhkes77v {
  fill: var(--svg-color--7328ff, #7328ff);
  d: path("M24 0H0v24h24z");
}

</style>
