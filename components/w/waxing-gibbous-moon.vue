<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVG2ogPrbEG" class="d2p45cc0h"/></defs><use href="#SVG2ogPrbEG" class="ehej3-bmx"/><clipPath id="SVGaTIvMdVj"><use href="#SVG2ogPrbEG"/></clipPath><path clip-path="url(#SVGaTIvMdVj)" class="v8feicbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:waxing-gibbous-moon" /></template>
<style>
.d2p45cc0h {
  d: path("M127.76 64c0 35.22-28.54 63.76-63.77 63.76C28.79 127.76.24 99.22.24 64S28.79.24 64 .24c35.22 0 63.76 28.54 63.76 63.76");
}

.ehej3-bmx {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.v8feicbeh {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M142.84 64c0 35.22-25.83 63.76-57.68 63.76c-31.86 0-57.69-28.54-57.69-63.76S53.29.23 85.16.23c31.85.01 57.68 28.55 57.68 63.77");
}

</style>
