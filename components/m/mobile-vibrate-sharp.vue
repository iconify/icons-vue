<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk8yl3y0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-vibrate-sharp" /></template>
<style>
.vk8yl3y0j {
  fill: currentColor;
  d: path("M1.462 14.5v-5h1v5zm2.769 2v-9h1v9zm17.307-2v-5h1v5zm-2.769 2v-9h1v9zM6.808 20V4h10.384v16zm5.78-11.914q.22-.222.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.547t.549.22t.548-.22");
}

</style>
