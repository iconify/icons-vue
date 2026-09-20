<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="zd6xt4l5p"/><path class="jytas1b9q"/><path class="it73ghb0t"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:phb-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.it73ghb0t {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.687 10.816l.328-.337l.333.337l-.334.61zm-5.932.26l-.298-.87l6.046 2.543l.384.672l-.525 3.797l-.46-.426l.76-3.37zm12.491 0l.298-.87l-6.046 2.543l-.385.672l.526 3.797l.46-.426l-.76-3.37zm-7.879-.425L4 6.2l.634 1.737l6.112 3.427zm3.266 0L20 6.2l-.634 1.737l-6.112 3.427zm-8.344-.908l-.477-1.322l6.11 3.282l.377.7zm13.423 0l.477-1.322l-6.111 3.282l-.377.7z");
}

.jytas1b9q {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.988 14.1c.014-.028.045-.012.06 0l.29 3.399l-.32.302l-.336-.302c.096-1.121.292-3.371.306-3.399m-.656-2.48l.306-.38l.371.789l.377-.788l.307.38l-.684 1.47z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zd6xt4l5p {
  fill: var(--svg-color--e61e28, #e61e28);
  d: path("M24 0H0v24h24z");
}

</style>
