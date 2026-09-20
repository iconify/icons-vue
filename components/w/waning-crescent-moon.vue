<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGVCJyre1L" class="lqaxk-bhz"/></defs><use href="#SVGVCJyre1L" class="j71m3fb1u"/><clipPath id="SVGqo8gwc1f"><use href="#SVGVCJyre1L"/></clipPath><path clip-path="url(#SVGqo8gwc1f)" class="oz2sp1ngd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:waning-crescent-moon" /></template>
<style>
.j71m3fb1u {
  fill: var(--svg-color--fcc21b, #fcc21b);
}

.lqaxk-bhz {
  d: path("M127.76 64c0 35.22-28.55 63.77-63.76 63.77C28.78 127.77.23 99.22.23 64C.23 28.79 28.78.23 64 .23c35.21 0 63.76 28.56 63.76 63.77");
}

.oz2sp1ngd {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M142.83 64c0 35.22-25.82 63.77-57.68 63.77S27.46 99.23 27.46 64C27.46 28.79 53.28.23 85.15.23c31.86 0 57.68 28.56 57.68 63.77");
}

</style>
