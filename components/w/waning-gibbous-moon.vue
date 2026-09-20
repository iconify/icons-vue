<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGXbqNgdSG" class="hpis9n1hq"/></defs><use href="#SVGXbqNgdSG" class="ehej3-bmx"/><clipPath id="SVGJLTtkdsk"><use href="#SVGXbqNgdSG"/></clipPath><path clip-path="url(#SVGJLTtkdsk)" class="l2fix9jku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:waning-gibbous-moon" /></template>
<style>
.ehej3-bmx {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.hpis9n1hq {
  d: path("M.23 64c0 35.22 28.54 63.77 63.77 63.77c35.21 0 63.77-28.54 63.77-63.77C127.77 28.79 99.22.23 64 .23S.23 28.79.23 64");
}

.l2fix9jku {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M-14.84 64c0 35.22 25.82 63.77 57.69 63.77c31.85 0 57.68-28.54 57.68-63.77C100.53 28.79 74.7.23 42.85.23C10.98.23-14.84 28.79-14.84 64");
}

</style>
