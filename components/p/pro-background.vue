<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="npi53oiwi"/><path class="zobwjhb4e"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pro-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.npi53oiwi {
  fill: var(--svg-color--38a6fa, #38a6fa);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zobwjhb4e {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.867 17.291c0 .31-.298.575-.609.575H8.551a.606.606 0 0 1-.593-.603v-.197c0-.029.028-.424.283-.903c.424-.79 1.215-1.355 2.346-1.75c1.623-.54 3.617-.87 4.946-2.031c.962-.818 1.239-2.098 1.267-3.339c.49.352 1.067.709 1.067 1.392zm-3.199-8.248c0 .621-.01 1.28-.463 1.703c-1.075.99-2.934 1.22-4.268 1.664c-2.064.677-3.082 1.863-3.563 2.737c-.084.17-.17.338-.226.508c0 .028-.015.028-.015.056v-5.248c0-.62.468-.987.552-1.043l4.75-3.104c.537-.367 1.102 0 1.102 0l2.131 1.401zM20 17.178v-6.715c0-.31-.085-1.861-1.526-2.82l-1.14-.8V4.511c0-.34-.33-.512-.641-.512h-.864c-.339 0-.629.173-.629.511v.922l-1.447-.921c-.877-.565-2.262-.79-3.478 0L5.526 7.615C5.244 7.784 4 8.715 4 10.436v6.715c0 .648.141 1.185.452 1.636c.226.367.566.649.961.846A3.9 3.9 0 0 0 6.827 20h10.375c.028 0 .706 0 1.413-.367c.424-.197.735-.48.99-.846c.254-.423.395-.96.395-1.609");
}

</style>
