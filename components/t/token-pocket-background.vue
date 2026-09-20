<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="k8azy9cjc"/><path fill="url(#SVGcFY1H3gS)" class="dibk8qumx"/><path class="l_urh7xob"/><path class="ls5vgx_ij"/><path class="mu9u_4ijg"/></g><defs><linearGradient id="SVGcFY1H3gS" x1="15.911" x2="14.986" y1="12.999" y2="12.999" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".967" class="emat65brk"/><stop offset="1" class="vc--wpv5i"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:token-pocket-background" /></template>
<style>
.dibk8qumx {
  d: path("M14.983 10.936v4.03q.17.036.337.06q.247.036.495.038h.03v-3.207a.92.92 0 0 1-.862-.921");
}

.emat65brk {
  stop-color: var(--svg-color--dfdfdf, #dfdfdf);
}

.ft5dv1b6b {
  fill: none;
}

.k8azy9cjc {
  fill: var(--svg-color--2980fe, #2980fe);
  d: path("M24 0H0v24h24z");
}

.l_urh7xob {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.984 10.936h-3.175v5.773c0 .272.217.491.487.491h2.194a.487.487 0 0 0 .486-.49v-5.774zM10.274 6.8H4.487A.49.49 0 0 0 4 7.29v2c0 .272.217.491.487.491H6.35v6.928c0 .272.217.491.487.491h2.081c.27 0 .487-.219.487-.49V9.78h.853c.816 0 1.483-.672 1.483-1.494A1.46 1.46 0 0 0 10.274 6.8");
}

.ls5vgx_ij {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.912 6.8c-2.261 0-4.103 1.85-4.103 4.136a4.13 4.13 0 0 0 3.175 4.03v-4.03c0-.513.411-.928.92-.928s.922.415.922.928a.93.93 0 0 1-.929.928v3.2c.082 0 .157 0 .24-.007C18.293 14.928 20 13.132 20 10.928A4.097 4.097 0 0 0 15.912 6.8");
}

.mu9u_4ijg {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.912 15.064v-3.2h-.067v3.208q.034-.01.067-.008");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

</style>
