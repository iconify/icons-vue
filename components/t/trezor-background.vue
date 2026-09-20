<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="h1ia9mx0v"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:trezor-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h1ia9mx0v {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.966 7.713C15.966 5.683 14.177 4 12 4S8.032 5.685 8.032 7.713V8.9H6.4v8.537L12 20l5.6-2.565V8.936h-1.632zm-5.911 0c0-.957.855-1.722 1.944-1.722c1.09 0 1.945.765 1.945 1.722V8.9h-3.89zm5.289 8.345l-3.345 1.532l-3.344-1.532v-5.13h6.689z");
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
