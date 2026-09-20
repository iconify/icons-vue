<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="vbtegvjep"/><path class="rid-yw6ol"/><path class="osn33ybhm"/><path class="owyjf_70l"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:snx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.osn33ybhm {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.965 10.75c.495.015.92.735.92 1.25s-.425 1.235-.92 1.25H10.52c-2.35-.03-4.515-2.36-4.515-4.755c0-2.4 2.165-4.465 4.515-4.495h6.305C17.32 4.015 18 4.43 18 5.225c0 .79-.415 1.25-1.175 1.275H10.52A2.045 2.045 0 0 0 8.5 8.495c0 1.35.69 2.255 2.02 2.255h2.45z");
}

.owyjf_70l {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.035 13.25c-.495-.015-.92-.735-.92-1.25s.425-1.235.92-1.25h2.445c2.35.03 4.52 2.36 4.52 4.755c0 2.4-2.17 4.465-4.52 4.495H7.175C6.44 19.98 6.02 19.6 6 18.795A1.265 1.265 0 0 1 7.175 17.5h6.305c1.05 0 2.02-.8 2.02-1.995c0-1.35-.69-2.255-2.02-2.255z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rid-yw6ol {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-45, 0.45);
  d: path("m6.1 18.35l9.11-12.676c.43-.76 2.08-.575 2.77-.305L9.045 17.794c-.365.575-2.17.615-2.95.55z");
}

.vbtegvjep {
  fill: var(--svg-color--1b1230, #1b1230);
  d: path("M24 0H0v24h24z");
}

</style>
