<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8mthqbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:play-arrow" /></template>
<style>
.p8mthqbzg {
  fill: currentColor;
  d: path("M9 17.192V6.808L17.154 12z");
}

</style>
