<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="c8zzf1x2s"/><path class="yyxwfw_iz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mcb-background" /></template>
<style>
.c8zzf1x2s {
  fill: var(--svg-color--59efec, #59efec);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.yyxwfw_iz {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.399 16.4c-.305 0-.496-.353-.348-.64l3.903-7.503c.212-.406.61-.657 1.042-.657h1.806c.303 0 .495.354.346.64l-3.903 7.502c-.211.406-.61.658-1.041.658zm7.005 0H9.599c-.305 0-.496-.353-.347-.64l3.903-7.502c.21-.406.61-.658 1.041-.658h1.806c.304 0 .496.354.347.64l-3.904 7.502c-.21.406-.609.658-1.041.658m5.216-5.79l-.874 1.694a1.33 1.33 0 0 0 0 1.21l1.162 2.254c.202.39.581.632.992.632h1.72c.29 0 .473-.34.33-.614l-2.67-5.176a.365.365 0 0 0-.66 0");
}

</style>
