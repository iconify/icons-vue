<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG79BOnegS)" class="v_2pxp47s"/><path class="xdi3-6hfs"/></g><defs><radialGradient id="SVG79BOnegS" cx="0" cy="0" r="1" gradientTransform="matrix(0 25.3016 -17.8098 0 12.024 3.502)" gradientUnits="userSpaceOnUse"><stop offset=".031" class="t_s4jjcam"/><stop offset="1" class="a5wymhb4q"/></radialGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:usde-background" /></template>
<style>
.a5wymhb4q {
  stop-color: var(--svg-color--1c1c1c, #1c1c1c);
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t_s4jjcam {
  stop-color: var(--svg-color--3a3a3a, #3a3a3a);
}

.v_2pxp47s {
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  d: path("M24 0H0v24h24z");
}

.xdi3-6hfs {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 4a8 8 0 0 1 8 8a8 8 0 0 1-8 8a8 8 0 1 1 0-16m-1.28 1.415a6.7 6.7 0 0 0-5.423 6.577a6.7 6.7 0 0 0 5.423 6.576v-.628a6.085 6.085 0 0 1 0-11.897zm2.56.632a6.086 6.086 0 0 1 4.796 5.945a6.085 6.085 0 0 1-4.796 5.944v.628a6.697 6.697 0 0 0 0-13.144zM11.648 7.2v1.063h-.177q-.882-.002-1.424.459q-.53.449-.53 1.21v.562q.001.645.416 1.075c.274.283.665.472 1.16.562l1.768.312q.449.073.706.325a.8.8 0 0 1 .267.606v.669q-.001.449-.353.73q-.357.27-.935.27h-1.092c-.39 0-.71-.134-.951-.396q-.352-.408-.354-1.055h-.705q0 .637.246 1.128q.255.48.706.75a2.03 2.03 0 0 0 1.041.263h.218v1.063h.706v-1.063h.205c.595 0 1.08-.152 1.445-.46q.548-.466.549-1.23v-.669q0-.634-.422-1.042q-.423-.413-1.19-.562l-1.764-.332c-.296-.054-.525-.164-.698-.333a.85.85 0 0 1-.246-.615v-.562q0-.45.332-.71q.334-.27.895-.27h1.111q.524 0 .837.344q.316.346.316.919h.706c0-.582-.173-1.055-.513-1.407q-.51-.541-1.346-.541h-.226V7.2z");
}

</style>
