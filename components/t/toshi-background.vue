<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path fill="url(#SVG5Ncwic5C)" class="u05zzu6yb"/><path fill="url(#SVG0d2E4dUd)" class="m06u68aty"/><path fill="url(#SVGA650NeQy)" class="nxpe6wbxy"/></g><defs><linearGradient id="SVG5Ncwic5C" x1="4.8" x2="19.669" y1="7.831" y2="7.551" gradientUnits="userSpaceOnUse"><stop class="jadp8hbtx"/><stop offset=".43" class="nzbo6_o9j"/><stop offset=".75" class="lnkjy5but"/><stop offset=".93" class="l72ulrbnc"/><stop offset="1" class="kbtb4mb-r"/></linearGradient><linearGradient id="SVG0d2E4dUd" x1="4" x2="9.717" y1="9.934" y2="20.916" gradientUnits="userSpaceOnUse"><stop class="x6j39p1ip"/><stop offset="1" class="qv8r1ubyt"/></linearGradient><linearGradient id="SVGA650NeQy" x1="14.316" x2="14.316" y1="10.812" y2="18.526" gradientUnits="userSpaceOnUse"><stop class="v_pky4bfx"/><stop offset=".3" class="pbnpudxul"/><stop offset=".48" class="q6qt_ybka"/><stop offset="1" class="xdqm3bc4k"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:toshi-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jadp8hbtx {
  stop-color: var(--svg-color--380d78, #380d78);
}

.kbtb4mb-r {
  stop-color: var(--svg-color--a7acc2, #a7acc2);
}

.l72ulrbnc {
  stop-color: var(--svg-color--8fd5b8, #8fd5b8);
}

.lnkjy5but {
  stop-color: var(--svg-color--7bf29e, #7bf29e);
}

.m06u68aty {
  d: path("m7.79 14.712l.866-3.9l1.365 3.31l-.316 1.347l1.874 1.937v1.12z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.nxpe6wbxy {
  d: path("m16.21 14.712l-.867-3.9l-1.364 3.31l.316 1.347l-1.874 1.937v1.12z");
}

.nzbo6_o9j {
  stop-color: var(--svg-color--56758a, #56758a);
}

.pbnpudxul {
  stop-color: var(--svg-color--84e7ae, #84e7ae);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q6qt_ybka {
  stop-color: var(--svg-color--70d78f, #70d78f);
}

.qv8r1ubyt {
  stop-color: var(--svg-color--77e397, #77e397);
}

.u05zzu6yb {
  d: path("M4 5.474v1.692l1.638 1.621l3.57.969v.758l1.436 3.553v1.175l1.343 1.486v.03l.013-.013l.013.013v-.03l1.343-1.486v-1.179l1.431-3.554v-.757l3.58-.969L20 7.166V5.474l-.434 1.174l-1.204.725l-3.57.619l-2.78-.615v-.004h-.025v.004l-2.779.615l-3.57-.62l-1.204-.724z");
}

.v_pky4bfx {
  stop-color: var(--svg-color--a69bd7, #a69bd7);
}

.x6j39p1ip {
  stop-color: var(--svg-color--24153e, #24153e);
}

.xdqm3bc4k {
  stop-color: var(--svg-color--3d5f5e, #3d5f5e);
}

</style>
