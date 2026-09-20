<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t__-0m9fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:phone-iphone-outline-sharp" /></template>
<style>
.t__-0m9fl {
  fill: currentColor;
  d: path("M6 22V2h12v20zm1-4.461V21h10v-3.462zm5 2.5q.31 0 .54-.23t.23-.54t-.23-.54T12 18.5t-.54.23t-.23.54t.23.539t.54.23m-5-3.5h10V5.5H7zM7 4.5h10V3H7zm0 13.039V21zM7 4.5V3z");
}

</style>
