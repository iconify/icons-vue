<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="krvcgg3xd"/><path class="p-27kibql"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pnk-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.krvcgg3xd {
  fill: var(--svg-color--3b3b3d, #3b3b3d);
  d: path("M24 0H0v24h24z");
}

.p-27kibql {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.622 11.57l6.368-2.738l-.928 6.886zm.54-6.269l5.085 2.156l-6.15 2.379zM7.433 12.87l5.527 3.886l-5.391 1.38zm8.802-4.137L20 12.498l-4.758 3.47zM9.594 18.808l4.66-1.2h.005l.819 1.544zm5.592-1.611l4.076-2.99h.006l-3.274 4.55zm1.354-9.774l.797-1.604l2.156 4.556zm-.194-2.368l-5.181-.207l4.278 1.84zm-12.187 5.25l3.629-4.513l-1.201 5.02zM4 11.189l2.44.507h-.006l.109 5.397z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
