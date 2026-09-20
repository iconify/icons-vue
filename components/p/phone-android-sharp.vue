<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qucdmlbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:phone-android-sharp" /></template>
<style>
.qucdmlbcc {
  fill: currentColor;
  d: path("M10 20h4v-1h-4zm-5 3V1h14v22zm2-7h10V6H7z");
}

</style>
