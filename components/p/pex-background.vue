<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGJKISHI7R)" class="r4i437pya"/><path class="ioic37bnk"/><path clip-rule="evenodd" class="e3chy5byl"/><path clip-rule="evenodd" class="fo6hnnr9c"/><path clip-rule="evenodd" class="hzjdrev-k"/></g><defs><linearGradient id="SVGJKISHI7R" x1="8.782" x2="12.563" y1="6.071" y2="13.594" gradientUnits="userSpaceOnUse"><stop class="m-oqq_zzq"/><stop offset="1" class="b9_zjab9h"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pex-background" /></template>
<style>
.b9_zjab9h {
  stop-color: var(--svg-color--0db775, #0db775);
}

.e3chy5byl {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M19.416 12.146a7.416 7.416 0 1 1-14.833 0a7.416 7.416 0 0 1 14.833 0m-5.995-4.851c-.33.367-.998 1.162-1.045 1.412h.33l1.74-1.412zm-1.497 1.412h.15c.585.01 1.148.222 1.592.602q.114.108.207.235q.634.9 1.171 1.86l.022.036c.128.22.243.419.34.575a3 3 0 0 1 0 2.838A3.87 3.87 0 0 1 12 16.707a3.87 3.87 0 0 1-3.407-1.854a3 3 0 0 1 0-2.838c.103-.165.225-.377.357-.612l.06-.101c.314-.533.697-1.183 1.117-1.758c.48-.658 1.35-.828 1.797-.837");
}

.fo6hnnr9c {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.418a7.417 7.417 0 1 0-.001-14.835a7.417 7.417 0 0 0 0 14.835m0-.626A6.79 6.79 0 1 0 12 5.21a6.79 6.79 0 0 0 0 13.58");
}

.ft5dv1b6b {
  fill: none;
}

.hzjdrev-k {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16m0-.706A7.296 7.296 0 0 0 19.294 12A7.295 7.295 0 1 0 12 19.294");
}

.ioic37bnk {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.328 10.547q-.066.084-.137.178c-.603.771-1.501 1.924-1.544 2.607c-.06.988 1.083 1.962 2.353 1.962s2.414-.974 2.353-1.962c-.042-.683-.94-1.84-1.543-2.612l-.349-.452c-.098-.136-.287-.15-.46-.15c-.151-.005-.382.042-.462.15q-.088.123-.21.28");
}

.m-oqq_zzq {
  stop-color: var(--svg-color--c2f2df, #c2f2df);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
