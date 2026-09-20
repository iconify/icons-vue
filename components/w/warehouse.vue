<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q09py2osy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:warehouse" /></template>
<style>
.q09py2osy {
  fill: currentColor;
  d: path("M3 20V7.673l9-3.596l9 3.596V20h-5v-8H8v8zm6.558 0v-1.538h1.538V20zm1.673-3v-1.538h1.538V17zm1.673 3v-1.538h1.538V20z");
}

</style>
