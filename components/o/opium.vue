<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG0XqTcbks)" clip-rule="evenodd" class="bgwiic2ni"/><defs><linearGradient id="SVG0XqTcbks" x1="3.175" x2="20.765" y1="12.355" y2="12.355" gradientUnits="userSpaceOnUse"><stop class="htuyfj4va"/><stop offset=".23" class="gtyxjdrjw"/><stop offset=".34" class="zpooz44go"/><stop offset=".46" class="ne6cwwvqh"/><stop offset=".59" class="ditsm_g4r"/><stop offset=".7" class="icn-tcbuf"/><stop offset=".83" class="fjl-5cbkl"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:opium" /></template>
<style>
.bgwiic2ni {
  fill-rule: evenodd;
  d: path("M3 12.25c.01-2.17 1.25-6.5 6.18-6.5c.62.03 2.125.325 3.18 1.26c1.325 1.165 1.53 1.25 2.205 1.25c.54 0 1.165-.235 1.41-.35c.225-.1.825-.3 1.41-.3c.735 0 3.615.68 3.615 4.365S18.165 16.4 17.475 16.4a4.1 4.1 0 0 1-1.635-.33c-.3-.13-.75-.325-1.3-.325c-.49 0-1.415.675-1.82 1.01c-.51.5-1.98 1.495-3.755 1.495c-2.215 0-5.965-1.66-5.965-6m4 .1C6.955 11.235 7.445 9 9.765 9h.02c.145 0 .865-.02 1.865.625l.095.06c.99.64 1.49.96 2.62.96c.935 0 1.675-.385 1.93-.575c.293-.187.628-.3.975-.33c.45 0 1.73.44 1.73 2.25s-1.33 2.305-1.73 2.305c-.32 0-.785-.23-.975-.35a3.9 3.9 0 0 0-1.93-.57a3.8 3.8 0 0 0-1.9.57c-.46.35-1.62 1.055-2.6 1.055c-1.215 0-2.86-1.23-2.86-2.65z");
}

.ditsm_g4r {
  stop-color: var(--svg-color--9736b6, #9736b6);
}

.fjl-5cbkl {
  stop-color: var(--svg-color--1a7bd9, #1a7bd9);
}

.ft5dv1b6b {
  fill: none;
}

.gtyxjdrjw {
  stop-color: var(--svg-color--ffed03, #ffed03);
}

.htuyfj4va {
  stop-color: var(--svg-color--4fef8f, #4fef8f);
}

.icn-tcbuf {
  stop-color: var(--svg-color--6453c5, #6453c5);
}

.ne6cwwvqh {
  stop-color: var(--svg-color--f62a81, #f62a81);
}

.zpooz44go {
  stop-color: var(--svg-color--fd9d37, #fd9d37);
}

</style>
