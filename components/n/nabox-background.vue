<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="n220zzgng"/><path class="fa4svacvv"/><path clip-rule="evenodd" class="ja7nqacij"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nabox-background" /></template>
<style>
.fa4svacvv {
  fill: var(--svg-color--fff, #fff);
  d: path("m4.89 8.444l6.666 4V20l-2.222-1.333v-5.334L7.11 12v5.333L4.89 16z");
}

.ft5dv1b6b {
  fill: none;
}

.ja7nqacij {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12.444 20v-8L5.333 7.778L12 4l7.11 4v8l-2.221 1.333v-8l-2.223 1.334v8zM9.777 7.778L12 6.444L14.666 8l-2.222 1.333z");
}

.n220zzgng {
  fill: var(--svg-color--2ac98b, #2ac98b);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
