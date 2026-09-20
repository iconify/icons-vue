<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="fevkm9b_a"/><path clip-rule="evenodd" class="sopm8t1sg"/><path clip-rule="evenodd" class="l_lvypaan"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:meter-background" /></template>
<style>
.fevkm9b_a {
  fill: var(--svg-color--010e35, #010e35);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.l_lvypaan {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m4 14.879l7.023-5.76l-.291 2.395l4.099-2.329l-.208 2.274L20 9.742l-7.293 4.028l.545-2.292l-4.213 2.476l.279-1.758z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sopm8t1sg {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M19.129 11.136q.05.424.051.864c0 3.976-3.214 7.2-7.18 7.2a7.18 7.18 0 0 1-6.518-4.174l1.149-.58a5.9 5.9 0 0 0 5.368 3.465c3.256 0 5.896-2.646 5.896-5.911q0-.09-.003-.181zM11.999 4.8a7.18 7.18 0 0 1 6.671 4.53l-1.229.392A5.9 5.9 0 0 0 12 6.09c-3.255 0-5.895 2.646-5.895 5.911l.002.121l-1.203.986A7 7 0 0 1 4.818 12C4.82 8.023 8.034 4.8 12 4.8");
}

</style>
