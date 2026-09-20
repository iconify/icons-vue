<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="h37zbxbsf"/><path class="dsuif_bzo"/><path class="ef_58gvyc"/><path class="rjf3ieunk"/><path class="vsvh8sbqi"/><path class="jzapiokjn"/><path class="klqmw4a8c"/><path class="ms2-yhb1h"/><path class="k0tjbq0ky"/><path class="pw5q0lb8b"/><path class="s0ahwbbjo"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sakai-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.dsuif_bzo {
  fill: var(--svg-color--55cf98, #55cf98);
  d: path("m12 8l-3.556 2v4L12 16z");
}

.ef_58gvyc {
  fill: var(--svg-color--1a6882, #1a6882);
  d: path("m4.889 8l3.555 2v4L4.89 16z");
}

.ft5dv1b6b {
  fill: none;
}

.h37zbxbsf {
  fill: var(--svg-color--348aa7, #348aa7);
  d: path("M8.444 10V6L4.89 8z");
}

.jzapiokjn {
  fill: var(--svg-color--bce784, #bce784);
  d: path("M15.556 6L12 8L8.444 6L12 4z");
}

.k0tjbq0ky {
  fill: var(--svg-color--57c795, #57c795);
  d: path("M15.556 6L12 8l3.556 2z");
}

.klqmw4a8c {
  fill: var(--svg-color--48b081, #48b081);
  d: path("m12 8l3.556 2v4L12 16z");
}

.ms2-yhb1h {
  fill: var(--svg-color--1a6882, #1a6882);
  d: path("m19.111 8l-3.555 2v4l3.555 2z");
}

.pw5q0lb8b {
  fill: var(--svg-color--0d3e4f, #0d3e4f);
  d: path("m19.111 16l-3.555-2L12 16v4z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rjf3ieunk {
  fill: var(--svg-color--76e8b5, #76e8b5);
  d: path("M8.444 6L12 8l-3.556 2z");
}

.s0ahwbbjo {
  fill: var(--svg-color--348aa7, #348aa7);
  d: path("M15.556 10V6l3.555 2z");
}

.vsvh8sbqi {
  fill: var(--svg-color--12556b, #12556b);
  d: path("m4.889 16l3.555-2L12 16v4z");
}

</style>
