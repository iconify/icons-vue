<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldnwg1bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pergola-sharp" /></template>
<style>
.ldnwg1bsy {
  fill: currentColor;
  d: path("M3 21V2h2v2h14V2h2v19h-2V10H5v11zm8 0v-3H8v-2h8v2h-3v3z");
}

</style>
