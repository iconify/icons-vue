<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m47js9b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:risk-pool" /></template>
<style>
.m47js9b7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.441 20.407q-.717.093-1.441.093q-.233 0-.466-.01q-.233-.009-.465-.029q-.232-.019-.463-.048q-.231-.028-.459-.067q-.229-.038-.455-.086q-.227-.047-.45-.104t-.442-.124t-.435-.141t-.427-.159t-.416-.177q-.206-.092-.406-.193t-.394-.21t-.381-.226t-.368-.242t-.353-.256t-.338-.271q-.164-.139-.321-.285t-.305-.297q-.148-.152-.286-.309q-.139-.158-.269-.321q-.13-.164-.249-.332q-.12-.169-.23-.342t-.21-.351q-.1-.177-.189-.359q-.089-.181-.168-.366q-.078-.185-.146-.373t-.124-.378t-.102-.383t-.08-.387t-.057-.39t-.035-.391Q2.5 12.696 2.5 12.5h13.6m3.8 0h1.6q0 .751-.166 1.489t-.492 1.437M8.5 9.5H15a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H8.5A1.5 1.5 0 0 1 7 11a1.5 1.5 0 0 1 1.5-1.5m1-3H16A1.5 1.5 0 0 1 17.5 8A1.5 1.5 0 0 1 16 9.5H9.5A1.5 1.5 0 0 1 8 8a1.5 1.5 0 0 1 1.5-1.5m-1-3H15A1.5 1.5 0 0 1 16.5 5A1.5 1.5 0 0 1 15 6.5H8.5A1.5 1.5 0 0 1 7 5a1.5 1.5 0 0 1 1.5-1.5m9.5 11V21m-2.75-2.75L18 21l2.75-2.75");
}

</style>
