<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jse0oby8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-landscape-long-outline-sharp" /></template>
<style>
.jse0oby8f {
  fill: currentColor;
  d: path("M5 12.866h1V17h12.98V7.196L20 6.773V18H5zM14.23 5h1.924v.923h3.165l.681.85l-2.217 6.593H3.523l-.546-.812l2.294-6.631H7.77V5h1.923v.923h4.539zm4.772 1.923H5.998l-1.877 5.443H17.1zM6 17h13.167zM5.998 6.923h13.004z");
}

</style>
