<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="fw1lu45uc"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wait-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fw1lu45uc {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M11.059 4.941H4v.471h.287c.461 0 .654.494.654.96v4.193c0 1.139-.565 1.44-.941 1.45c.941.112.96.955.941 1.364v4.165c0 .47-.193 1.044-.654 1.044H4v.471h7.059v-.47h-.15c-.575 0-1.036-.674-1.036-1.257V16.08c0-1.317 1.416-3.256 2.127-4.066c-1.812-2.183-2.174-3.6-2.132-4.037V6.584c0-.584.47-1.172 1.04-1.172h.15zM6.824 9.483v-3.6a.47.47 0 1 0-.942 0v4.564c0 1.11.527 1.567.894 1.567c-.894.109-.908 1.38-.894 1.798v4.306a.47.47 0 1 0 .942 0v-3.482a2.75 2.75 0 0 1 1.882-2.622a3.1 3.1 0 0 1-1.882-2.531M12.94 4.94H20v.471h-.287c-.466 0-.654.494-.654.96v4.193c0 1.139.564 1.44.941 1.45c-.941.112-.96.955-.941 1.364v4.165c0 .47.193 1.044.654 1.044H20v.471h-7.059v-.47h.15c.575 0 1.036-.674 1.036-1.257V16.08c0-1.317-1.416-3.256-2.127-4.066c1.812-2.183 2.174-3.6 2.132-4.037V6.584c0-.584-.47-1.172-1.04-1.172h-.15zm4.236 4.542v-3.6a.47.47 0 1 1 .94 0v4.564c0 1.11-.526 1.567-.893 1.567c.894.109.908 1.38.894 1.798v4.306a.47.47 0 1 1-.941 0v-3.482a2.75 2.75 0 0 0-1.883-2.622a3.1 3.1 0 0 0 1.883-2.531");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
