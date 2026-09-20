<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="z9qv4ebgm"/><path class="azj2qqbfp"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rep-background" /></template>
<style>
.azj2qqbfp {
  fill: var(--svg-color--fff, #fff);
  d: path("m19.057 15.073l-1.506-2.533a.196.196 0 0 0-.27-.064l-.98.631a.197.197 0 0 0-.062.265l.86 1.446a.1.1 0 0 1-.03.133l-5.015 3.236a.09.09 0 0 1-.104 0l-5.018-3.236a.1.1 0 0 1-.03-.133l.86-1.446a.197.197 0 0 0-.063-.264l-.978-.633a.19.19 0 0 0-.22.008a.2.2 0 0 0-.051.057l-1.506 2.533a.39.39 0 0 0 .124.528l6.722 4.337a.38.38 0 0 0 .418 0L18.93 15.6a.39.39 0 0 0 .127-.528M7.643 10.886l.948.639a.2.2 0 0 0 .147.025a.18.18 0 0 0 .117-.091l3.064-5.378a.09.09 0 0 1 .08-.047a.09.09 0 0 1 .08.047l3.067 5.378a.19.19 0 0 0 .193.093a.2.2 0 0 0 .07-.027l.95-.639a.204.204 0 0 0 .059-.268l-3.663-6.426A.38.38 0 0 0 12.432 4h-.864a.37.37 0 0 0-.322.192l-3.663 6.426a.204.204 0 0 0 .06.268");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.z9qv4ebgm {
  fill: var(--svg-color--2ae7a8, #2ae7a8);
  d: path("M24 0H0v24h24z");
}

</style>
