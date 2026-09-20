<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path fill="url(#SVGD6mAKbXW)" clip-rule="evenodd" class="cs-9x3b0p"/></g><defs><linearGradient id="SVGD6mAKbXW" x1="4.156" x2="19.791" y1="12.315" y2="12.315" gradientUnits="userSpaceOnUse"><stop class="htuyfj4va"/><stop offset=".23" class="gtyxjdrjw"/><stop offset=".34" class="zpooz44go"/><stop offset=".46" class="ne6cwwvqh"/><stop offset=".59" class="ditsm_g4r"/><stop offset=".7" class="icn-tcbuf"/><stop offset=".83" class="fjl-5cbkl"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:opium-background" /></template>
<style>
.cs-9x3b0p {
  fill-rule: evenodd;
  d: path("M4 12.222c.009-1.929 1.111-5.778 5.493-5.778c.551.027 1.89.29 2.827 1.12c1.178 1.036 1.36 1.111 1.96 1.111c.48 0 1.036-.208 1.253-.31c.2-.09.734-.267 1.254-.267c.653 0 3.213.604 3.213 3.88s-2.52 3.933-3.133 3.933a3.65 3.65 0 0 1-1.454-.293c-.266-.116-.666-.29-1.155-.29c-.436 0-1.258.6-1.618.899c-.453.444-1.76 1.328-3.338 1.328C7.333 17.555 4 16.08 4 12.222m3.556.089c-.04-.991.395-2.978 2.457-2.978h.018c.129 0 .769-.018 1.658.556l.084.053c.88.569 1.325.853 2.33.853c.83 0 1.488-.342 1.715-.51a1.9 1.9 0 0 1 .867-.294c.4 0 1.537.391 1.537 2s-1.182 2.049-1.538 2.049c-.284 0-.697-.204-.866-.311a3.5 3.5 0 0 0-1.716-.507a3.4 3.4 0 0 0-1.689.507c-.409.31-1.44.938-2.31.938c-1.08 0-2.543-1.094-2.543-2.356z");
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

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.ne6cwwvqh {
  stop-color: var(--svg-color--f62a81, #f62a81);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zpooz44go {
  stop-color: var(--svg-color--fd9d37, #fd9d37);
}

</style>
