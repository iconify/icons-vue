<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_o2zvb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:spellcheck-outline" /></template>
<style>
.f_o2zvb8u {
  fill: currentColor;
  d: path("m14.1 21.308l-3.558-3.558l.708-.708l2.85 2.85l5.689-5.688l.707.708zM3.77 16L8.503 3h1.119l4.696 13h-1.146l-1.304-3.8H6.196L4.854 16zm2.78-4.7h5.016L9.05 4.323h-.061z");
}

</style>
