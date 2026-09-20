<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="yvqruqbwj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xlm-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.yvqruqbwj {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.512 12.748A5.9 5.9 0 0 1 7.2 9.154a5.64 5.64 0 0 1 2.005-2.092a5.4 5.4 0 0 1 2.744-.786c.97-.01 1.923.241 2.76.727l1.268-.668a6.58 6.58 0 0 0-7.051-.571a6.86 6.86 0 0 0-2.698 2.58a7.2 7.2 0 0 0-.978 4.19c.019.25-.035.5-.154.72a1.26 1.26 0 0 1-.514.512L4 14.072v1.43L20 7.07V5.64zM20 8.501L7.37 15.152L4 16.929v1.429l13.491-7.11q.047.375.047.753a5.9 5.9 0 0 1-.734 2.85a5.64 5.64 0 0 1-2.008 2.094a5.4 5.4 0 0 1-2.748.785a5.4 5.4 0 0 1-2.762-.733l-.068.038l-1.195.63a6.58 6.58 0 0 0 7.05.572a6.86 6.86 0 0 0 2.698-2.58a7.2 7.2 0 0 0 .979-4.194c-.019-.25.035-.499.154-.72c.117-.216.296-.394.514-.51L20 9.926z");
}

</style>
