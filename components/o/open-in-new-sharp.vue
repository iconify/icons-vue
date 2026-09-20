<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p33sbv5dk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:open-in-new-sharp" /></template>
<style>
.p33sbv5dk {
  fill: currentColor;
  d: path("M4 20V4h7.23v1H5v14h14v-6.23h1V20zm5.739-5.03l-.708-.709L18.292 5H14V4h6v6h-1V5.708z");
}

</style>
