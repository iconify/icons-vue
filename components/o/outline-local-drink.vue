<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_i0kabur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-local-drink" /></template>
<style>
.s_i0kabur {
  fill: currentColor;
  d: path("m3 2l2.01 18.23C5.13 21.23 5.97 22 7 22h10c1.03 0 1.87-.77 1.99-1.77L21 2zm14 18l-10 .01L5.89 10H18.1zm1.33-12H5.67l-.44-4h13.53zM12 19c1.66 0 3-1.34 3-3c0-2-3-5.4-3-5.4S9 14 9 16c0 1.66 1.34 3 3 3m0-5.09c.59.91 1 1.73 1 2.09c0 .55-.45 1-1 1s-1-.45-1-1c0-.37.41-1.19 1-2.09");
}

</style>
