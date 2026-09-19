<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="omxhwxbsh"/><path class="z87t5cc6q"/><path class="hfyicm81v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:privamatic" /></template>
<style>
.hfyicm81v {
  d: path("M17.806 35.762V14.834h6.852c3.873 0 7.013 3.147 7.013 7.028s-3.14 7.03-7.013 7.03h-6.852");
}

.omxhwxbsh {
  d: path("M37.693 13.76c2.37-.816 4.059-2.715 4.324-5.133q.11-1.577-.019-3.151a.666.666 0 0 0-.647-.62c-1.072-.034-2.318-.212-3.28-1.16a.54.54 0 0 0-.756 0c-.963.948-2.208 1.127-3.28 1.16a.666.666 0 0 0-.647.62a21 21 0 0 0-.02 3.151c.266 2.418 1.955 4.317 4.325 5.134z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z87t5cc6q {
  d: path("M45.265 20.807q.234 1.564.235 3.193c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5");
}

</style>
