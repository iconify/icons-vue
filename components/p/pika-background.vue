<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="rcfx3nsgz"/><path clip-rule="evenodd" class="jky6yj65q"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pika-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jky6yj65q {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M10.628 5.057c-1.164.354-2.022 1.561-2.022 4.107c0 2.434.543 3.583 1.576 4.421c.088.074.2.113.315.112c.272 0 .533-.18.533-.485V6.638c0-.941.597-2.638 2.682-2.638c2.603 0 4.591 2.448 4.591 5.164c0 2.594-1.358 5.347-4.916 6.104c-.315.063-.417.33-.417.64v3.185c0 .5-.325.907-.97.907c-.514 0-.97-.407-.97-.907v-3.19c0-.31-.28-.572-.586-.65c-1.843-.485-4.747-2.181-4.747-6.09c0-3.927 2.982-5.042 4.824-5.158a.485.485 0 0 1 .51.494c0 .243-.18.456-.403.558m2.342 7.927V6.463c0-.848.848-1.353 1.43-.732c.776.824 1.479 2.109 1.479 3.908c0 2.177-1.038 3.389-1.978 3.966c-.442.271-.931-.097-.931-.62");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rcfx3nsgz {
  fill: var(--svg-color--fce74f, #fce74f);
  d: path("M24 0H0v24h24z");
}

</style>
