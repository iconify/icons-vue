<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="g-bemhbtn"/><path class="wpt6hvbnz"/><path class="xmczlkbbo"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:uos-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g-bemhbtn {
  fill: var(--svg-color--7a51d1, #7a51d1);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wpt6hvbnz {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.499 11.55V4.5h3v7.05c0 .56-.515 1.45-1.455 1.45a1.5 1.5 0 0 1-1.545-1.45");
}

.xmczlkbbo {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 12.185V4.5h3v7.53c0 1.785 1.26 4.47 5 4.47c3.38 0 5-2.185 5-4.47V4.5h3v7.29c0 1.535-.52 7.66-8 7.71c-6.475.045-8-4.88-8-7.315");
}

</style>
