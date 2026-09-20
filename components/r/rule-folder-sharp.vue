<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4_lzfb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rule-folder-sharp" /></template>
<style>
.h4_lzfb1u {
  fill: currentColor;
  d: path("M3 19V5h6.596l2 2H21v12zm4.825-3.337l4.239-4.238l-.714-.713l-3.525 3.53l-1.406-1.405l-.707.713zm6.575 0l1.6-1.6l1.6 1.6l.688-.688l-1.6-1.6l1.6-1.6l-.688-.688l-1.6 1.6l-1.6-1.6l-.688.688l1.6 1.6l-1.6 1.6z");
}

</style>
