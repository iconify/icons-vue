<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6vxpcc5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:upscale-sparkle-fill" /></template>
<style>
.k6vxpcc5g {
  fill: currentColor;
  d: path("M2.989 4.999c.134-.028.261-.107.375-.177a4.9 4.9 0 0 0 1.458-1.458c.07-.114.149-.241.177-.375L5 2.986a1 1 0 0 1 2 0l.001.003c.028.134.107.261.177.375a4.9 4.9 0 0 0 1.458 1.458c.114.07.241.149.375.177L9.014 5a1 1 0 0 1 0 2l-.003.001c-.134.028-.261.107-.375.177a4.9 4.9 0 0 0-1.458 1.458c-.07.114-.149.241-.177.375L7 9.014a1 1 0 0 1-2 0l-.001-.003c-.028-.134-.107-.261-.177-.375a4.9 4.9 0 0 0-1.458-1.458c-.114-.07-.241-.149-.375-.177L2.986 7a1 1 0 0 1 0-2Zm10.304 4.294L17.586 5H16a1 1 0 0 1 0-2h4a.997.997 0 0 1 1 1v4a1 1 0 0 1-2 0V6.414l-4.293 4.293a.999.999 0 1 1-1.414-1.414M4 12h6a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2v-6a2 2 0 0 1 2-2");
}

</style>
