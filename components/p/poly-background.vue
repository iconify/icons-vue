<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gckg-7bjw"/><path class="fy4zxub-v"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:poly-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fy4zxub-v {
  fill: var(--svg-color--fff, #fff);
  d: path("m20 7.991l-.034-.542l-.16.451l-.886.789l-1.029.154l-.303-.286l.892-1.257l.92-.28l-.988.023l-1.44 1.057l-1.315-.097l-.051-.034l-1.892-.949l-1.12.229l-3.503 2.948l-1.674.543l-.703.815h-1.24l-.606 1.076l-.868.246l.811.126l.766-1.034l1.16.234l-.011 1.115l-.583 1.588l-.343 1.48l-.36.594l.914-.2l-.102-.617l.776-1.623l1.503-.605l.572-.972l.983-.72l1.937.292l1.96-.875l-.343 1.495h-.857l-.252 1.094l.743-.51l1.229-.536l1.097-1.531v-.738l.457.555l1.497.948l.857-.405l-.057-2.018l-.234-.788l1.114-.286z");
}

.gckg-7bjw {
  fill: var(--svg-color--3f4b80, #3f4b80);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
