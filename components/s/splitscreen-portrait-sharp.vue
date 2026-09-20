<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ov0zgskwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:splitscreen-portrait-sharp" /></template>
<style>
.ov0zgskwm {
  fill: currentColor;
  d: path("M8.385 17.616h7.23v-4.424h-7.23zm0-6.808h7.23V6.385h-7.23zM5 21V3h14v18z");
}

</style>
