<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3-3swbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-assistant-photo" /></template>
<style>
.l3-3swbio {
  fill: currentColor;
  d: path("m12.36 6l.08.39l.32 1.61H18v6h-3.36l-.08-.39l-.32-1.61H7V6zM14 4H5v17h2v-7h5.6l.4 2h7V6h-5.6z");
}

</style>
