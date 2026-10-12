<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6tllgxku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:megaphone-alt-sharp" /></template>
<style>
.l6tllgxku {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9.25h4v3.5h-4zm4.92-.38l7.16-2.99l.92-.38v11l-.92-.38l-7.16-2.99l-.92-.38v-3.5zm1.27 4.82l1.12.47l.69.29l-.16.73l-.93 4.09l-.16.73h-2.5l.14-.74l.97-5.12l.14-.74zm9.46-5.34L21.797 11l-2.647 2.65");
}

</style>
