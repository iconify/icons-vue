<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwpkvo38j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:skillet-cooktop-sharp" /></template>
<style>
.rwpkvo38j {
  fill: currentColor;
  d: path("M4 14.346V9h12V7.371l5.848-1.975l.318.939L17 8.07v6.275zM10 20v-2.884H3v-1h8V20zm3 0v-3.884h8v1h-7V20z");
}

</style>
