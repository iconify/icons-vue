<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8-lgrbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-cell-outline-sharp" /></template>
<style>
.p8-lgrbjx {
  fill: currentColor;
  d: path("M8 23.77q-.31 0-.54-.23T7.23 23t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23m4 0q-.31 0-.54-.23t-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23m4 0q-.31 0-.54-.23t-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23M6.808 19V1h10.384v18zm1-1h8.384v-1.5H7.808zm0-2.5h8.384v-11H7.808zm0-12h8.384V2H7.808zm0 0V2zm0 14.5v-1.5z");
}

</style>
