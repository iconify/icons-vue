<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="y52_pcbpy"/><path class="iz7m3_7rn"/><path clip-rule="evenodd" class="z5z36jpne"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:paribu-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iz7m3_7rn {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.717 11.56q.223-.138.36-.385q.135-.246.135-.649q0-.401-.136-.649a1 1 0 0 0-.36-.384a1.4 1.4 0 0 0-.52-.183a4 4 0 0 0-.613-.047h-1.44v2.526h1.44q.318 0 .614-.047q.294-.047.52-.183");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y52_pcbpy {
  fill: var(--svg-color--618138, #618138);
  d: path("M24 0H0v24h24z");
}

.z5z36jpne {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 20H4V4h16zM15.065 8.784q.324.352.474.805t.15.938q0 .474-.15.933a2.2 2.2 0 0 1-.474.81a2.35 2.35 0 0 1-.844.568q-.519.215-1.258.215h-1.82V16H9.46v-2.947H8.312V11.79h1.147V9.264H8.312V8h4.651q.74.001 1.258.215q.518.216.844.569");
}

</style>
