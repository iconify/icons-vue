<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts7adeb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:other-houses-sharp" /></template>
<style>
.ts7adeb7q {
  fill: currentColor;
  d: path("M5 20v-9.144l-1.934 1.49l-.604-.792L12 4.25l9.539 7.304l-.605.787L19 10.856V20zm3-5.23q-.31 0-.54-.23T7.23 14t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23m4 0q-.31 0-.54-.23t-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23m4 0q-.31 0-.54-.23t-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23");
}

</style>
