<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qkzwymbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:sagittarius" /></template>
<style>
.qkzwymbli {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M47.44 14.81v16.57h37.47L47.44 68.84l-15.6-15.6l-11.72 11.71l15.61 15.61l-20.92 20.91l11.72 11.72l20.91-20.92l15.61 15.6l11.71-11.71l-15.6-15.6l37.46-37.47v37.46h16.57V14.81z");
}

</style>
