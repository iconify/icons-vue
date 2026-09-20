<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gzqwrfb0d"/><path class="kgg-ixnwp"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xcp-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gzqwrfb0d {
  fill: var(--svg-color--ed1650, #ed1650);
  d: path("M24 0H0v24h24z");
}

.kgg-ixnwp {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.46 7h-2.948a.45.45 0 0 0-.321.13l-5.387 5.32a.48.48 0 0 1-.32.15h-.986a.48.48 0 0 1-.321-.15l-.644-.54a.47.47 0 0 1-.132-.327v-1a.47.47 0 0 1 .132-.33l.644-.714a.46.46 0 0 1 .32-.139h.986c.124 0 .234.058.321.139l.43.438c.174.18.47.18.643 0l1.036-1.052a.47.47 0 0 0 0-.657l-1.13-1.132A.45.45 0 0 0 9.462 7H6.506a.46.46 0 0 0-.321.136l-2.081 2.11c-.087.09-.107.213-.104.337v3c0 .124.023.24.104.328l2.087 1.976a.44.44 0 0 0 .321.114h2.956a.44.44 0 0 0 .322-.122l5.378-5.333c.082-.09.2-.143.321-.146h.993c.117 0 .233.058.321.146l.693.708c.085.088.105.206.104.328v.849c0 .122-.019.24-.104.328l-.693.716a.45.45 0 0 1-.321.125h-.993a.45.45 0 0 1-.32-.125l-.432-.36a.45.45 0 0 0-.634-.007l-1.149 1.343a.48.48 0 0 0-.154.328v2.782c0 .256.22.44.468.44h1.47c.25-.005.466-.19.462-.44v-1.1a.45.45 0 0 1 .45-.46h1.81c.12 0 .237-.048.321-.132l2.087-1.958a.47.47 0 0 0 .132-.329v-3a.47.47 0 0 0-.131-.328L17.78 7.13a.45.45 0 0 0-.32-.13");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
