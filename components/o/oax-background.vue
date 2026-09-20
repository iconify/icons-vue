<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="l3y_fzlzk"/><path class="eu62mu4op"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:oax-background" /></template>
<style>
.eu62mu4op {
  fill: var(--svg-color--fff, #fff);
  d: path("M10 15h-.8l2.68-6l1.824 4h-.8l-1.02-2zm4.6-.028L16.864 12L14.6 9h.8l1.896 2.424l-.432.576l.432.54L15.4 15h-1.6l-.44-1h.772zM17.724 12l-.428-.576L19.2 9h.8zm0 0L20 15h-.8l-1.904-2.46zM9.6 12c.02 1.552-1.192 3-2.8 3A2.755 2.755 0 0 1 4 12.2a3.7 3.7 0 0 1 .505-1.936l.528.692c-.212.384-.232.752-.232 1.244a2 2 0 0 0 2 2c1.263.028 2-1.052 2-2.148c0-1.16-.665-2.252-2-2.252c-.42 0-.768.132-1.04.312l-.608-.56A2.62 2.62 0 0 1 6.8 9c1.611-.028 2.843 1.452 2.8 3");
}

.ft5dv1b6b {
  fill: none;
}

.l3y_fzlzk {
  fill: var(--svg-color--1a467e, #1a467e);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
