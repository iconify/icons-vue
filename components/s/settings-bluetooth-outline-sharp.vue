<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uozxz1bxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-bluetooth-outline-sharp" /></template>
<style>
.uozxz1bxe {
  fill: currentColor;
  d: path("M7.46 23.54q-.23-.23-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23t-.54-.23m4 0q-.23-.23-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23t-.54-.23m4 0q-.23-.23-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23t-.54-.23m-3.96-4.232v-8.1l-5.1 5.1l-.708-.708l5.6-5.6l-5.6-5.6l.708-.708l5.1 5.1v-8.1h.5L17.008 5.7l-4.3 4.3l4.3 4.3L12 19.308zm1-1.927l3.092-3.081l-3.092-3.092zm0-8.589L15.592 5.7L12.5 2.62z");
}

</style>
