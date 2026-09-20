<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbmyrbmfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:meeting-room-outline-sharp" /></template>
<style>
.cbmyrbmfm {
  fill: currentColor;
  d: path("M4.5 20v-1h2V4h8v1h3v14h2v1h-3V6h-2v14zm3-15v14zm4.54 7.54q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23M7.5 19h6V5h-6z");
}

</style>
