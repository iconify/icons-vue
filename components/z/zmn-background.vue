<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGSGM2je7P)" class="x2l7wmziz"/><path fill="url(#SVGK6w1tddz)" class="r45-d5blw"/><path fill="url(#SVG6vizPHzD)" class="gqub3ybmf"/></g><defs><linearGradient id="SVGSGM2je7P" x1="4.111" x2="19.693" y1="12.356" y2="12.239" gradientUnits="userSpaceOnUse"><stop class="bi-rm9b8w"/><stop offset=".49" class="hw37etn1b"/><stop offset="1" class="ubwf88wyo"/></linearGradient><linearGradient id="SVGK6w1tddz" x1="4.669" x2="19.278" y1="11.28" y2="11.152" gradientUnits="userSpaceOnUse"><stop class="f19ycmbfz"/><stop offset=".51" class="ec7_8lqmf"/><stop offset="1" class="fmcu3kbgw"/></linearGradient><linearGradient id="SVG6vizPHzD" x1="6.161" x2="17.75" y1="12.767" y2="10.941" gradientUnits="userSpaceOnUse"><stop class="f1e0-qchn"/><stop offset=".5" class="wk87xcb6m"/><stop offset="1" class="j9e4aqgri"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zmn-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.bi-rm9b8w {
  stop-color: var(--svg-color--929595, #929595);
}

.ec7_8lqmf {
  stop-color: var(--svg-color--373a3c, #373a3c);
}

.f19ycmbfz {
  stop-color: var(--svg-color--15191b, #15191b);
}

.f1e0-qchn {
  stop-color: var(--svg-color--959797, #959797);
}

.fmcu3kbgw {
  stop-color: var(--svg-color--181c1e, #181c1e);
}

.ft5dv1b6b {
  fill: none;
}

.gqub3ybmf {
  d: path("M6.717 8.209a6.61 6.61 0 0 1 6.67.023a.1.1 0 0 0 .047-.019l2.364-1.648q.048-.032 0-.061a6.657 6.657 0 0 0-9.333 1.835l.023.024q.016.015.024 0a1 1 0 0 1 .205-.154m9.585-1.261L5.877 14.155c-.033.018-.038.046-.029.08q.236.629.598 1.195a.06.06 0 0 0 .047.01l.019-.01l10.747-7.46a.07.07 0 0 0 .029-.07a7 7 0 0 0-.897-.948a.07.07 0 0 0-.09-.004m1.92 2.779L7.805 16.953a.06.06 0 0 1-.07-.005a9 9 0 0 1-.916-.953q-.033-.036.005-.065L17.6 8.466a.06.06 0 0 1 .07 0c.01 0 .014.009.02.018q.335.531.56 1.154a.04.04 0 0 1 0 .047a.1.1 0 0 1-.029.046zm-.636 5.824a6.9 6.9 0 0 1-3.208.995a6.57 6.57 0 0 1-3.597-.869a.07.07 0 0 0-.075.005L8.324 17.35a.03.03 0 0 0-.014.024q0 .008.004.013l.01.01a6.65 6.65 0 0 0 9.29-1.817c.033-.046.024-.06-.028-.028");
}

.hw37etn1b {
  stop-color: var(--svg-color--f2f1ee, #f2f1ee);
}

.j9e4aqgri {
  stop-color: var(--svg-color--989a9a, #989a9a);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r45-d5blw {
  d: path("M19.338 11.945A7.27 7.27 0 0 1 5.346 14.72a7.29 7.29 0 0 1 1.567-7.922a7.287 7.287 0 0 1 12.425 5.147");
}

.ubwf88wyo {
  stop-color: var(--svg-color--949797, #949797);
}

.wk87xcb6m {
  stop-color: var(--svg-color--ededeb, #ededeb);
}

.x2l7wmziz {
  d: path("M11.884 4h.387c2.041.093 3.779.803 5.213 2.149q2.241 2.102 2.508 5.278v1.065a7.8 7.8 0 0 1-1.98 4.703a7.95 7.95 0 0 1-8.747 2.336A7.945 7.945 0 0 1 6.39 6.382Q8.605 4.132 11.884 4");
}

</style>
