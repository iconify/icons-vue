<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6ca26f4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:warehouse-outline-sharp" /></template>
<style>
.d6ca26f4x {
  fill: currentColor;
  d: path("M4 19h3v-8h10v8h3V8.35l-8-3.2l-8 3.2zm-1 1V7.673l9-3.596l9 3.596V20h-5v-8H8v8zm6.558 0v-1.538h1.538V20zm1.673-3v-1.538h1.538V17zm1.673 3v-1.538h1.538V20zM7 11h10z");
}

</style>
