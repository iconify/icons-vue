<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="vw1_-9b3b"/><path class="kssujxbvz"/><path clip-rule="evenodd" class="y6g4ezn6c"/><path class="fs341o3ff"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:troy-background" /></template>
<style>
.fs341o3ff {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.426 10.75v2.762c0 .108.04.19.17.19c.146 0 .17-.112.17-.19V10.87c0-.16.109-.235.153-.232h2.288c.197 0 .282.167.282.208c0 .204.007.44 0 .603a.22.22 0 0 1-.214.21h-1.018c-.05 0-.173.007-.231.1c-.058.091-.007.2.027.241l1.436 1.6c.069.068.229.15.307.034c.082-.112-.024-.214-.089-.286L10.537 12h.816a.504.504 0 0 0 .477-.44v-.748c-.01-.402-.35-.51-.514-.514H8.919c-.364 0-.51.293-.49.453zm-.896-.452H4.174c-.051 0-.174.034-.174.174c0 .108.116.153.174.166h1.528v2.911c0 .068.065.153.17.153c.11 0 .17-.071.17-.153v-2.91H7.53c.072.003.215-.008.215-.16c0-.15-.143-.178-.215-.181");
}

.ft5dv1b6b {
  fill: none;
}

.kssujxbvz {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.596 10.461v1.056c.013.173.132.483.524.483h1.008v1.566c0 .071.054.136.17.136c.13 0 .17-.082.17-.136V12H19.5a.525.525 0 0 0 .5-.524V10.46a.164.164 0 0 0-.167-.163c-.112 0-.173.082-.173.163v.967c0 .072-.089.218-.26.232c-.115.006-.781.004-1.404.002l-.794-.002c-.072-.014-.26-.075-.266-.232a30 30 0 0 1 0-.967c0-.054-.017-.163-.17-.163s-.17.109-.17.163");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vw1_-9b3b {
  fill: var(--svg-color--82deff, #82deff);
  d: path("M24 0H0v24h24z");
}

.y6g4ezn6c {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M13.082 10.298h2.24c.252 0 .593.16.593.585v2.196c0 .225-.15.623-.593.623h-2.24c-.194 0-.565-.255-.568-.623c-.005-.254-.003-.93-.002-1.515l.002-.68c.003-.195.126-.586.568-.586m.17.34h1.961c.198 0 .361.086.361.426v1.923c0 .18-.034.375-.388.375h-1.964c-.157 0-.368-.058-.368-.35c-.004-.208-.002-.908-.001-1.464l.001-.573c.004-.156.041-.337.399-.337");
}

</style>
