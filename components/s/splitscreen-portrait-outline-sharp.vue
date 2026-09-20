<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4_k08bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:splitscreen-portrait-outline-sharp" /></template>
<style>
.x4_k08bac {
  fill: currentColor;
  d: path("M8 18h8v-5H8zm0-7h8V6H8zM4 22V2h16v20zm2-2h12V4H6zM18 4H6z");
}

</style>
