<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="fuexkebhx"/><path class="lzryrsbhf"/><path class="kowaom1sy"/><path class="wif_zxzyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:smart-bulb" /></template>
<style>
.fuexkebhx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 17.25v-1.5a3 3 0 0 0-1.1-2.3a6 6 0 1 1 7.7 0a3 3 0 0 0-1.1 2.3v1.5Z");
}

.kowaom1sy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 11.25h.01");
}

.lzryrsbhf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 8.75a3.25 3.25 0 0 1 4.5 0");
}

.wif_zxzyy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 20.5h4.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
