<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="y16-tab9u"/><path class="myppw8brp"/><path class="lnlgjvbej"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:yfi-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lnlgjvbej {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.118 7.848c0 1.722.735 2.543 2.482 3.755V10.34c-.97-.77-1.415-1.377-1.415-2.506c0-1.541 1.26-2.79 2.814-2.79s2.815 1.249 2.815 2.79c0 .505-.137 1-.399 1.432L14 7.514l-1.074.25l.85 3.496l3.489-.926l-.286-1.056l-1.556.413a3.8 3.8 0 0 0 .46-1.843C15.882 5.723 14.144 4 12 4S8.118 5.723 8.118 7.848m7.764 8.304c0-1.722-.74-2.555-2.486-3.767v1.261c.97.77 1.419 1.39 1.419 2.52c0 1.54-1.26 2.789-2.815 2.789s-2.814-1.249-2.814-2.79c0-.523.145-1.013.398-1.432L10 16.486l1.074-.25l-.85-3.496l-3.488.926l.286 1.056l1.556-.413a3.8 3.8 0 0 0-.46 1.843c0 2.125 1.738 3.848 3.881 3.848c2.144 0 3.883-1.723 3.883-3.848");
}

.myppw8brp {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.4 7.2h1.2v10h-1.2z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y16-tab9u {
  fill: var(--svg-color--006ae3, #006ae3);
  d: path("M24 0H0v24h24z");
}

</style>
