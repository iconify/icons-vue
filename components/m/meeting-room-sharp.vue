<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w670zknqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:meeting-room-sharp" /></template>
<style>
.w670zknqi {
  fill: currentColor;
  d: path("M4.5 20v-1h2V4h8v1h3v14h2v1h-3V6h-2v14zm7.54-7.46q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23");
}

</style>
