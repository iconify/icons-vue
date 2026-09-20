<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lex20mbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:turn-sharp-left-outline-sharp" /></template>
<style>
.lex20mbqb {
  fill: currentColor;
  d: path("M16.5 20v-5.884h-10v-8.2l-2.1 2.1l-.708-.708L7 4l3.308 3.308l-.708.708l-2.1-2.1v7.2h10V20z");
}

</style>
