<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kgpby7oyo"/><path class="px929s9az"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vulnerable-dependency" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kgpby7oyo {
  d: path("m13.95 15.207l-3.582 2.047q-.099.056-.204.1q-.105.043-.215.072t-.223.044q-.112.014-.226.014t-.226-.014t-.223-.044t-.215-.072q-.105-.044-.204-.1l-5.25-3q-.1-.057-.192-.127q-.091-.07-.173-.151t-.152-.172t-.129-.191q-.057-.1-.102-.206q-.044-.107-.074-.218t-.045-.226t-.015-.229V7.016q0-.115.015-.229q.015-.115.045-.226t.074-.218q.045-.106.102-.206q.058-.099.129-.191q.07-.091.152-.172t.173-.151t.192-.127l5.25-3q.099-.056.204-.1q.105-.043.215-.072t.223-.044q.112-.014.226-.014t.226.014q.113.015.223.044t.215.072t.204.1l5.25 3q.1.057.192.127q.091.07.173.151t.152.172q.071.092.129.191q.057.1.102.206q.044.107.074.218t.045.226q.015.114.015.229v5.718q0 .09-.009.18");
}

.px929s9az {
  d: path("m2.5 6l7 3.75l7-3.75m-7 3.75v8m10.075-1.252l1.206 2.489a1.75 1.75 0 0 1-1.574 2.513h-2.414a1.75 1.75 0 0 1-1.574-2.513l1.206-2.489a1.75 1.75 0 0 1 3.15 0M18 16.5v1.75M18 20h.01");
}

</style>
