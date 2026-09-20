<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="jeshxqexs"/><path clip-rule="evenodd" class="cbm-fpbrs"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:skeb-background" /></template>
<style>
.cbm-fpbrs {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m4.49 9.899l1.2 1.213l.79-.787l-1.208-1.208l-.791.786zm3.097-3.097L8.795 8.01L8 8.797L6.791 7.588l.791-.786zm2.31-2.311l1.21 1.209l-.787.786l-1.21-1.209zm2.707 15.26l7.145-7.146a.856.856 0 0 0 0-1.209l-7.145-7.145a.856.856 0 0 0-1.209 0l-.396.395l1.053 1.05l-1.732 1.732L9.266 6.38l-.577.578l1.053 1.049L8.009 9.74L6.956 8.69l-.578.578l1.053 1.053l-1.733 1.733L4.645 11l-.395.4a.853.853 0 0 0 0 1.204l7.145 7.145a.856.856 0 0 0 1.209 0m2.057-6.48c0-.51-.129-.928-.387-1.244a2.65 2.65 0 0 0-1.235-.764a7 7 0 0 0-.422-.133a2.4 2.4 0 0 1-.387-.152a.9.9 0 0 1-.28-.2a.42.42 0 0 1-.102-.293a.5.5 0 0 1 .209-.422a.87.87 0 0 1 .542-.16c.178 0 .356.036.547.111c.186.076.373.187.564.342l.684-1.364a4.5 4.5 0 0 0-2.057-.546a2.7 2.7 0 0 0-.95.16a2.02 2.02 0 0 0-1.178 1.146c-.112.29-.166.6-.16.911q-.002.501.15.822q.156.331.405.542a2 2 0 0 0 .573.342q.32.135.654.24l.48.178c.133.053.235.111.32.173c.08.063.142.134.177.205a.7.7 0 0 1 .049.266a.62.62 0 0 1-.204.445q-.206.2-.632.2a1.8 1.8 0 0 1-.742-.174a3 3 0 0 1-.764-.515l-.738 1.409a3.95 3.95 0 0 0 2.325.76a3.4 3.4 0 0 0 1.084-.165a2.3 2.3 0 0 0 .809-.467a1.9 1.9 0 0 0 .502-.715q.167-.422.168-.938z");
}

.ft5dv1b6b {
  fill: none;
}

.jeshxqexs {
  fill: var(--svg-color--30b396, #30b396);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
