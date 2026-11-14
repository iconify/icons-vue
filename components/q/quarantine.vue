<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pgmctk7lq"/><path class="ce7e_ofiz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:quarantine" /></template>
<style>
.ce7e_ofiz {
  d: path("M14.25 14h7.5v3c0 2.5-1.5 4.25-3.75 5c-2.25-.75-3.75-2.5-3.75-5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pgmctk7lq {
  d: path("M11.738 19.5H5.125q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T4.12 19.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257v-6.136q0-.291.063-.574q.064-.284.188-.547q.124-.262.302-.492q.179-.229.403-.414l5.875-4.838q.087-.072.18-.136q.094-.064.192-.12t.201-.103t.209-.086t.216-.067t.221-.048t.224-.029t.226-.01t.226.01t.224.029t.221.048t.216.067q.106.039.209.086t.201.103t.192.12t.18.136l5.875 4.838q.224.185.403.414q.178.23.302.492q.124.263.188.547q.063.283.063.574v.491");
}

</style>
