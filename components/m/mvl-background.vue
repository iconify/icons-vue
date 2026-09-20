<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="jcs8bbc1c"/><path clip-rule="evenodd" class="a9s3kcdah"/><path class="c7-seo36z"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mvl-background" /></template>
<style>
.a9s3kcdah {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M16.807 8.199c-.56 2.201-1.754 6.845-2.049 7.81c-.1.328-.283.816-.645 1.231c-.393.449-1.104.82-1.87.82c-.896 0-1.422-.354-1.864-.867c-.35-.407-.502-.893-.569-1.103l-.019-.059l-.01-.03l-2.039-7.84c.005.02-.015-.051-.108-.129c-.078-.064-.246-.165-.587-.165c-.431 0-.622.488-.622.981c0 .533-.444.97-.97.97a.98.98 0 0 1-.97-.97v-.724c0-.326.296-.896.67-1.326a2.46 2.46 0 0 1 1.893-.859c1.563 0 2.358 1.012 2.54 1.752l2.018 7.756l.005.013c.306.922 1.068.83 1.328-.022c.28-.911 1.466-5.526 2.032-7.75l.003-.014l.005-.014c.198-.693.99-1.72 2.532-1.72c.832 0 1.471.371 1.887.858c.388.456.602 1.037.602 1.55v8.743c0 .532-.444.97-.97.97a.973.973 0 0 1-.97-.964v-8.85a.54.54 0 0 0-.55-.381c-.31 0-.479.095-.568.169a.5.5 0 0 0-.134.16zM5.455 13.697c.536 0 .97.442.97.988v2.388a.98.98 0 0 1-.97.987a.98.98 0 0 1-.97-.987v-2.389a.98.98 0 0 1 .97-.987");
}

.c7-seo36z {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.256 12.377a.875.875 0 0 1 0-1.237l.58-.58a.875.875 0 0 1 1.237 0l.58.58a.875.875 0 0 1 0 1.236l-.58.58a.87.87 0 0 1-1.237 0z");
}

.ft5dv1b6b {
  fill: none;
}

.jcs8bbc1c {
  fill: var(--svg-color--072d3a, #072d3a);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
