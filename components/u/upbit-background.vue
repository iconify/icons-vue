<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="cruwa2bfx"/><path clip-rule="evenodd" class="hqec44bjj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:upbit-background" /></template>
<style>
.cruwa2bfx {
  fill: var(--svg-color--093687, #093687);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.hqec44bjj {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0m-7.061-1.469l-1.427 4.336h1.863l.605-1.844h2.133c.548-.004 1.164-.36 1.568-.91q.192-.261.304-.564l.012-.03l.011-.032l.27-.82c.276-.846-.125-1.535-.895-1.535h-4.248l.491 1.623zm2.488 1.534h-1.132l.648-1.974h1.132c.283 0 .43.253.328.564l-.278.846c-.102.311-.415.564-.698.564m-8.958 2.789q.072.01.145.013h3.78l1.428-4.335l-.84.224l1.557-1.623h-2.125L8.845 13.91h-.928a.34.34 0 0 1-.174-.042c-.165-.087-.224-.292-.148-.522l1.383-4.212H7.1L5.736 13.28s-.028.09-.033.112a1.5 1.5 0 0 0-.037.74q.016.075.043.145q.05.14.142.258a.85.85 0 0 0 .384.261a1 1 0 0 0 .234.058");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
