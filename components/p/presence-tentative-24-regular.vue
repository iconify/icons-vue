<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mty54xbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-tentative-24-regular" /></template>
<style>
.mty54xbbg {
  fill: currentColor;
  d: path("M11.678.005C5.303.17.166 5.308 0 11.683zM2.39 19.193a12 12 0 0 1-1.752-3.31L15.878.642a12 12 0 0 1 3.31 1.751zM23.356 8.125L8.12 23.36a12 12 0 0 1-3.312-1.75L21.606 4.813c.746.996 1.34 2.11 1.75 3.312m.635 4.201l-11.67 11.67c6.37-.17 11.5-5.301 11.67-11.67");
}

</style>
