<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="v_zj17bbo"><path class="pho8mcc0v"/><ellipse class="kj1uidbmg"/></g><path class="mufg37brr"/><path class="s8tnswb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:thermometer" /></template>
<style>
.kj1uidbmg {
  cx: 32.5px;
  cy: 52.966px;
  rx: 12.436px;
  ry: 10.634px;
}

.mufg37brr {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M37.75 46.09V19.365H27.249V46.09c-2.792 1.498-4.652 4.145-4.652 7.169c0 4.677 4.434 8.47 9.903 8.47s9.903-3.793 9.903-8.47c0-3.02-1.861-5.671-4.653-7.169");
}

.pho8mcc0v {
  d: path("M39.09 47.912c0 2.674-2.951 4.838-6.595 4.838s-6.596-2.164-6.596-4.838V4.772c0-2.672 2.953-4.839 6.596-4.839S39.09 2.1 39.09 4.772z");
}

.s8tnswb6c {
  fill: var(--svg-color--1f2e35, #1f2e35);
  d: path("M27.639 20.381c-.338 0-.612-.454-.612-1.013c0-.56.274-1.013.612-1.013h6.796c.338 0 .612.454.612 1.013s-.274 1.013-.612 1.013zm0 6.974c-.338 0-.612-.453-.612-1.01c0-.56.274-1.015.612-1.015h6.796c.338 0 .612.455.612 1.015s-.274 1.01-.612 1.01zm0 6.975c-.338 0-.612-.453-.612-1.013s.274-1.013.612-1.013h6.796c.338 0 .612.454.612 1.013c0 .56-.274 1.013-.612 1.013zm0-20.924c-.338 0-.612-.454-.612-1.012c0-.56.274-1.013.612-1.013h6.796c.338 0 .612.454.612 1.013s-.274 1.012-.612 1.012z");
}

.v_zj17bbo {
  fill: var(--svg-color--d0d2d3, #d0d2d3);
}

</style>
