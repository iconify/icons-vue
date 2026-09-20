<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGElB4fdaE" x1="23.666%" x2="76.334%" y1="95.612%" y2="4.388%"><stop offset="0%" class="a_7v919ts"/><stop offset="19.11%" class="dwl1spjjz"/><stop offset="38.23%" class="lfvw0wbcj"/><stop offset="50%" class="kcaaivr8d"/><stop offset="67.32%" class="z0b2j4blv"/><stop offset="77.74%" class="m1bs88fev"/><stop offset="86.33%" class="mjhz23mfl"/><stop offset="93.88%" class="mu66mdbnf"/><stop offset="100%" class="d048q5y4w"/></linearGradient></defs><path fill="url(#SVGElB4fdaE)" class="lcgttxb9o"/><path class="heeazccbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:zoom-icon" /></template>
<style>
.a_7v919ts {
  stop-color: var(--svg-color--0845bf, #0845bf);
}

.d048q5y4w {
  stop-color: var(--svg-color--4f90ee, #4f90ee);
}

.dwl1spjjz {
  stop-color: var(--svg-color--0950de, #0950de);
}

.heeazccbd {
  fill: var(--svg-color--fff, #fff);
  d: path("M204.032 207.872H75.008c-8.448 0-16.64-4.608-20.48-12.032c-4.608-8.704-2.816-19.2 4.096-26.112l89.856-89.856H83.968c-17.664 0-32-14.336-32-32h118.784c8.448 0 16.64 4.608 20.48 12.032c4.608 8.704 2.816 19.2-4.096 26.112l-89.6 90.112h74.496c17.664 0 32 14.08 32 31.744");
}

.kcaaivr8d {
  stop-color: var(--svg-color--0b5cff, #0b5cff);
}

.lcgttxb9o {
  d: path("M256 128c0 13.568-1.024 27.136-3.328 40.192c-6.912 43.264-41.216 77.568-84.48 84.48C155.136 254.976 141.568 256 128 256s-27.136-1.024-40.192-3.328c-43.264-6.912-77.568-41.216-84.48-84.48C1.024 155.136 0 141.568 0 128s1.024-27.136 3.328-40.192c6.912-43.264 41.216-77.568 84.48-84.48C100.864 1.024 114.432 0 128 0s27.136 1.024 40.192 3.328c43.264 6.912 77.568 41.216 84.48 84.48C254.976 100.864 256 114.432 256 128");
}

.lfvw0wbcj {
  stop-color: var(--svg-color--0b59f6, #0b59f6);
}

.m1bs88fev {
  stop-color: var(--svg-color--1665fc, #1665fc);
}

.mjhz23mfl {
  stop-color: var(--svg-color--246ff9, #246ff9);
}

.mu66mdbnf {
  stop-color: var(--svg-color--387ff4, #387ff4);
}

.z0b2j4blv {
  stop-color: var(--svg-color--0e5efe, #0e5efe);
}

</style>
