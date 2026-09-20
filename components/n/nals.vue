<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp2mmxbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nals" /></template>
<style>
.qp2mmxbfa {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("M6.075 5H9.5v2h-3v4.58l-.5.35v.55l.5.325V17h3v2H6.075L4.5 17v-4H3v-2h1.5V7zm11.85 0H14.5v2h3v4.58l.5.35v.55l-.5.325V17h-3v2h3.425l1.575-2v-4H21v-2h-1.5V7zM11.5 9.97c.24-.225.55-.47 1.16-.47c1.065 0 1.84.985 1.84 2.01v2.99H13v-3.105c-.04-.29-.175-.895-.67-.895c-.355 0-.83.5-.83.79v3.21H10v-5h1.5z");
}

</style>
