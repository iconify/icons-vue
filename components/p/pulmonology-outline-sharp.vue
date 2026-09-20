<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h22c9j9kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pulmonology-outline-sharp" /></template>
<style>
.h22c9j9kq {
  fill: currentColor;
  d: path("M11 21H2v-7.175L5.3 5H10v4H8V7H6.7L4 14.175V19h5v-3h2zm11 0h-9v-5h2v3h5v-4.825L17.3 7H16v2h-2V5h4.7l3.3 8.825zm-10-9.6L9.4 14L8 12.6l3-3V2h2v7.6l3 3l-1.4 1.4z");
}

</style>
