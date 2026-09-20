<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGMAqzYbZP)" class="r4i437pya"/><path class="mwy43drnh"/></g><defs><linearGradient id="SVGMAqzYbZP" x1="19.794" x2="1.633" y1="16.081" y2="3.592" gradientUnits="userSpaceOnUse"><stop class="j_y72bb9r"/><stop offset=".5" class="b0lhikban"/><stop offset="1" class="le5qt5b3x"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xvs-background" /></template>
<style>
.b0lhikban {
  stop-color: var(--svg-color--20bdff, #20bdff);
}

.ft5dv1b6b {
  fill: none;
}

.j_y72bb9r {
  stop-color: var(--svg-color--5433ff, #5433ff);
}

.le5qt5b3x {
  stop-color: var(--svg-color--5cffa2, #5cffa2);
}

.mwy43drnh {
  fill: var(--svg-color--fff, #fff);
  d: path("m19.73 7.984l-5.863 10.023a2 2 0 0 1-1.746.995a2.03 2.03 0 0 1-1.745-.995l-1.026-1.75l-.005-.007a.02.02 0 0 1 0-.017l.005-.006l.02-.006l.015.006a1.69 1.69 0 0 0 2.121.2c.215-.14.395-.326.52-.55l4.907-8.394a1.65 1.65 0 0 0-1.03-2.445l-.015-.005l-.005-.007l-.002-.008l.002-.009l.005-.006l.015-.005h2.08a2.04 2.04 0 0 1 1.751 1a1.97 1.97 0 0 1-.005 1.986m-6.938-2.986H10.76a.02.02 0 0 0-.011.007a.02.02 0 0 0-.004.013v.01l.015.01a1.02 1.02 0 0 1 .59.6a1 1 0 0 1-.075.835l-2.96 5.057a1.02 1.02 0 0 1-.721.485a1.04 1.04 0 0 1-.85-.25a.02.02 0 0 0-.015.006a.02.02 0 0 0-.005.014v.015l1.04 1.78a1.32 1.32 0 0 0 1.15.66a1.34 1.34 0 0 0 1.156-.66l3.876-6.612a1.3 1.3 0 0 0-.49-1.795c-.2-.115-.43-.175-.665-.175m-7.053 0c-.7 0-1.35.425-1.62 1.07a1.79 1.79 0 0 0 1.625 2.43a1.8 1.8 0 0 0 1.75-1.77c0-.95-.815-1.73-1.75-1.73z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
