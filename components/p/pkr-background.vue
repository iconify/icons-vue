<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGY5GXkbXE)" class="a_8pog9fn"/><path fill="url(#SVGfCcxNban)" clip-rule="evenodd" class="vsqr1_bfv"/><path fill="url(#SVGAxgFERcC)" clip-rule="evenodd" class="zwuuiqb9s"/></g><defs><linearGradient id="SVGY5GXkbXE" x1="7.548" x2="16.392" y1="6.595" y2="16.638" gradientUnits="userSpaceOnUse"><stop class="ebq2mgboy"/><stop offset="1" class="cu8te_b2r"/></linearGradient><linearGradient id="SVGfCcxNban" x1="7.74" x2="17.75" y1="6.145" y2="17.44" gradientUnits="userSpaceOnUse"><stop class="nmstq8dsr"/><stop offset=".47" class="l_3ghu9fj"/><stop offset="1" class="prkolbb5i"/></linearGradient><linearGradient id="SVGAxgFERcC" x1="8.432" x2="15.247" y1="9.11" y2="14.999" gradientUnits="userSpaceOnUse"><stop class="q_1v5rwdg"/><stop offset="1" class="vgwsibb6s"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pkr-background" /></template>
<style>
.a_8pog9fn {
  d: path("M12.01 19.664c4.253 0 7.7-3.443 7.7-7.69s-3.447-7.69-7.7-7.69s-7.7 3.443-7.7 7.69s3.447 7.69 7.7 7.69");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.cu8te_b2r {
  stop-color: var(--svg-color--575757, #575757);
}

.ebq2mgboy {
  stop-color: var(--svg-color--fffcf8, #fffcf8);
}

.ft5dv1b6b {
  fill: none;
}

.l_3ghu9fj {
  stop-color: var(--svg-color--e20c7b, #e20c7b);
}

.nmstq8dsr {
  stop-color: var(--svg-color--fb18ad, #fb18ad);
}

.prkolbb5i {
  stop-color: var(--svg-color--1d010d, #1d010d);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q_1v5rwdg {
  stop-color: var(--svg-color--ff14a4, #ff14a4);
}

.vgwsibb6s {
  stop-color: var(--svg-color--1c000c, #1c000c);
}

.vsqr1_bfv {
  fill-rule: evenodd;
  d: path("m16.37 5.59l.13-.21a8.04 8.04 0 0 1 2.55 2.815l-.22.11a7.8 7.8 0 0 0-2.46-2.715m3.38 6.87H20c-.08 1.37-.5 2.65-1.185 3.75l-.255-.055a7.7 7.7 0 0 0 1.19-3.7zm-4.3 6.485l.115.225a8 8 0 0 1-3.54.83v-.25c1.23 0 2.395-.29 3.43-.8zm-7.53-.355l-.14.205a8.05 8.05 0 0 1-2.585-2.59l.2-.15c.63 1.025 1.5 1.9 2.525 2.535M4.25 11.9H4c.015-1.31.35-2.545.92-3.63l.235.09a7.7 7.7 0 0 0-.905 3.54M12 4h.055v.25h-.05c-1.37 0-2.65.35-3.765.965l-.1-.225A8 8 0 0 1 12.005 4zm7.51 8a7.506 7.506 0 1 1-15.011.004a7.506 7.506 0 0 1 15.011-.009zm.25 0a7.75 7.75 0 0 1-4.79 7.163a7.75 7.75 0 0 1-8.45-1.684a7.756 7.756 0 1 1 13.24-5.484z");
}

.zwuuiqb9s {
  fill-rule: evenodd;
  d: path("M12.166 5.375c-.005.46-.325 1.58-1.595 2.73l-1.3 1.19c-.825.76-1.55 1.425-1.9 1.705h2.2l.08.01c.35.035.94.1.94.545V12h-4.02l-.065.1c-.175.27-.505.785-.505 1.335c0 .79.95 2.565 2.86 2.565c1.525 0 2.725-.815 3.13-1.125c.545.4 1.975 1.125 3.385 1.125C17.14 16 18 14.98 18 13.78c0-.965-.47-1.56-.63-1.74c.02.19-.11.66-.8 1.035l.29 1.425H15.5l-.205-1.265l-.345 1.265h-1.33l.48-2.255h2.13V12h-2.075l.21-1h2.31s-2.39-2.025-3.055-2.77c-.66-.735-1.445-1.75-1.46-2.85zM10.846 11l-.205 1h1.38l.16-1zm-.725 3.5h1.325l.33-1.215l.405 1.215h1.39l-.54-1.845l.315-.42h-2.81zm2.03-2.5l.82-1h1.335l-.775 1zm-2.975 5.5c.88-.1 2.535-.735 2.825-2.5a2.99 2.99 0 0 0 2.825 2.5zm-2.365-3h1.35l.24-1.23h.655c.34-.03 1.05-.2 1.19-.655l.1-.35h-3.12z");
}

</style>
