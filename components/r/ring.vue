<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="zzznd6b4l"/><path class="rskkor31g"/><path class="k2e0gcbhr"/><path class="bulvqiapy"/><path class="bwudp4bir"/><path class="c_2qq56vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:ring" /></template>
<style>
.bulvqiapy {
  fill: var(--svg-color--5dadec, #5dadec);
  d: path("m29 5l-4-5h-7v5h1z");
}

.bwudp4bir {
  fill: var(--svg-color--8ccaf7, #8ccaf7);
  d: path("M18 5h11l-11 9z");
}

.c_2qq56vt {
  fill: var(--svg-color--9aaab4, #9aaab4);
  d: path("M25 13a3 3 0 0 1-3 3h-8a3 3 0 1 1 0-6h8a3 3 0 0 1 3 3");
}

.k2e0gcbhr {
  fill: var(--svg-color--8ccaf7, #8ccaf7);
  d: path("m29 5l-4-5H11L7 5h11z");
}

.rskkor31g {
  fill: var(--svg-color--5dadec, #5dadec);
  d: path("m29 5l-4-5H11L7 5l11 9z");
}

.zzznd6b4l {
  fill: var(--svg-color--9aaab4, #9aaab4);
  d: path("M18 12c-6.627 0-12 5.373-12 12s5.373 12 12 12s12-5.373 12-12s-5.373-12-12-12m0 20a8 8 0 1 1 0-16a8 8 0 0 1 0 16");
}

</style>
