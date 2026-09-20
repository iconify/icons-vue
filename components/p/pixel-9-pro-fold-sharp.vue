<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxwcvub0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pixel-9-pro-fold-sharp" /></template>
<style>
.vxwcvub0d {
  fill: currentColor;
  d: path("M3 20V4h18v16zm9-1h8V5h-8zm-2-7.5v-1H5v1zm6-3.73q.31 0 .54-.23t.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23m-6-.27v-1H5v1z");
}

</style>
