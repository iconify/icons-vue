<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nk7-x1btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pergola" /></template>
<style>
.nk7-x1btt {
  fill: currentColor;
  d: path("M3 21V3q0-.425.288-.712T4 2t.713.288T5 3v1h14V3q0-.425.288-.712T20 2t.713.288T21 3v18h-2V10H5v11zm8 0v-3H8v-2h8v2h-3v3z");
}

</style>
