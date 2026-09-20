<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="f_ck94rfc"/><path class="htiekssfo"/><path class="wz1z0yb1y"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:upp-background" /></template>
<style>
.f_ck94rfc {
  fill: var(--svg-color--21a0b4, #21a0b4);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.htiekssfo {
  fill: var(--svg-color--fff, #fff);
  d: path("m17.716 12.733l-2.178 3.76a.76.76 0 0 1 .044.569a.808.808 0 0 1-1.435.231H9.902a.808.808 0 0 1-1.404-.773L6.31 12.742a.81.81 0 0 1 .058-1.609l2.12-3.662a.813.813 0 0 1 1.4-.782h4.267a.81.81 0 0 1 1.39.804l2.107 3.644a.8.8 0 0 1 .063 1.6zm2.088-1.476l-3.262-5.626a1.48 1.48 0 0 0-1.284-.742H8.742c-.533 0-1.022.284-1.289.742L4.2 11.258a1.47 1.47 0 0 0 0 1.48l3.258 5.63a1.48 1.48 0 0 0 1.284.743h6.516c.533 0 1.022-.28 1.289-.742l3.253-5.632a1.47 1.47 0 0 0 0-1.48z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wz1z0yb1y {
  fill: var(--svg-color--fff, #fff);
  d: path("m17.005 11.377l-1.369-2.369l-5.106 2.862v.014a.813.813 0 0 1-1.618 0a.81.81 0 0 1 1.311-.627l5.067-2.84l-.267-.462a.8.8 0 0 1-1.009-.587h-3.991a.813.813 0 0 1-1.022.578L7 11.39a.8.8 0 0 1-.031 1.134l1.524 2.63l5.222-3.013l-.004-.075a.813.813 0 0 1 1.618 0a.809.809 0 0 1-1.271.666l-5.227 3.014l.178.302a.805.805 0 0 1 1.009.56h4a.81.81 0 0 1 .99-.564l2.027-3.507A.8.8 0 0 1 17 11.382z");
}

</style>
