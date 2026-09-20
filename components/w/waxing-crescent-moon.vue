<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGiT24jezb" class="ynb9zacky"/></defs><use href="#SVGiT24jezb" class="j71m3fb1u"/><clipPath id="SVGkT4Wxd0m"><use href="#SVGiT24jezb"/></clipPath><path clip-path="url(#SVGkT4Wxd0m)" class="of7mvdb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:waxing-crescent-moon" /></template>
<style>
.j71m3fb1u {
  fill: var(--svg-color--fcc21b, #fcc21b);
}

.of7mvdb4i {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M-14.84 64.01c0 35.21 25.82 63.76 57.69 63.76c31.85 0 57.68-28.55 57.68-63.76C100.53 28.79 74.7.23 42.85.23c-31.87 0-57.69 28.55-57.69 63.78");
}

.ynb9zacky {
  d: path("M.24 64.01c0 35.21 28.54 63.76 63.76 63.76c35.21 0 63.77-28.55 63.77-63.76C127.77 28.79 99.22.23 64 .23S.24 28.78.24 64.01");
}

</style>
