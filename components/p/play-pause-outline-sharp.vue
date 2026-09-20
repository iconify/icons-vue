<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s39qlqbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:play-pause-outline-sharp" /></template>
<style>
.s39qlqbvb {
  fill: currentColor;
  d: path("M5 16.2V7.8l6 4.2zm8-.2V8h2v8zm4 0V8h2v8z");
}

</style>
