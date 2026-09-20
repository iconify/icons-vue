<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="lxrv8kpyl"/><path class="detk875mq"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:thales-background" /></template>
<style>
.detk875mq {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.221 9.776a5.78 5.78 0 0 0 3.116 5.13l-.004.009c.009.435.378 1.471 1.289 1.471c.725 0 .925-.658.934-.987v-.924c0-.654-.45-1.214-.65-1.312a3.557 3.557 0 0 1 .906-6.935a3.556 3.556 0 0 1 1.628 6.802c-.364.204-.55.804-.55 1.525v2.742c-.01.09-.108.267-.206.44l-.128.236l-.023.044c-.124.254-.186.378-.186.73c0 .373.289 1.253 1.311 1.253s1.245-1.067 1.245-1.254v-.03c0-.187 0-.476-.187-.743l-.147-.191c-.173-.214-.346-.431-.346-.72v-1.183c.009-.204.146-.591.302-.902a5.777 5.777 0 0 0 .542-10.096a5.778 5.778 0 0 0-8.846 4.895m4.214-1.778l3.343 3.334a2.8 2.8 0 0 1-1.68.667a2.374 2.374 0 0 1-2.32-2.388c0-.826.44-1.422.657-1.613");
}

.ft5dv1b6b {
  fill: none;
}

.lxrv8kpyl {
  fill: var(--svg-color--1e1c57, #1e1c57);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
