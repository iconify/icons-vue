<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="y49eywuhk"/><path class="fe1kq7bbi"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tnt-background" /></template>
<style>
.fe1kq7bbi {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.5 13.89a47.4 47.4 0 0 0-7 0l-.235-3.1a50.4 50.4 0 0 1 7.47 0zm-2 4.86q-1.5-.091-3 0c-.03-1.06-.08-1.44-.11-2.5c1.28-.066 1.92-.06 3.2 0zM4 5.943l.515 3.625c.3-.53.45-.8.76-1.32c4.512-.673 9.1-.665 13.61.025c.25.515.365.775.6 1.295c.2-1.45.305-2.175.515-3.625a46.5 46.5 0 0 0-16 0");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y49eywuhk {
  fill: var(--svg-color--f94081, #f94081);
  d: path("M24 0H0v24h24z");
}

</style>
