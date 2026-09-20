<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="h0hcmwb_t"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:stellar-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h0hcmwb_t {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.512 12.754A5.97 5.97 0 0 1 7.2 9.13a5.67 5.67 0 0 1 2.005-2.11a5.37 5.37 0 0 1 2.744-.792a5.36 5.36 0 0 1 2.76.733l1.268-.674c-1-.76-2.197-1.22-3.449-1.324a6.53 6.53 0 0 0-3.603.749a6.9 6.9 0 0 0-2.697 2.602a7.3 7.3 0 0 0-.978 4.225a1.33 1.33 0 0 1-.154.726c-.12.221-.298.4-.514.515L4 14.09v1.442l16-8.503V5.587zM20 8.472L7.37 15.178L4 16.97v1.44l13.491-7.169q.047.38.047.76a6 6 0 0 1-.734 2.873a5.67 5.67 0 0 1-2.008 2.112a5.37 5.37 0 0 1-2.748.791a5.36 5.36 0 0 1-2.762-.738l-.068.038l-1.195.635c1 .76 2.196 1.22 3.447 1.325a6.53 6.53 0 0 0 3.603-.748a6.9 6.9 0 0 0 2.698-2.6a7.3 7.3 0 0 0 .979-4.23a1.33 1.33 0 0 1 .154-.726c.117-.219.296-.398.514-.515l.582-.31z");
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
