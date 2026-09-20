<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2mb--i-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:video-call-outline-sharp" /></template>
<style>
.c2mb--i-l {
  fill: currentColor;
  d: path("M2 20V4h16v6.5l4-4v11l-4-4V20zm2-2h12V6H4zm0 0V6zm5-2h2v-3h3v-2h-3V8H9v3H6v2h3z");
}

</style>
