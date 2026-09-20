<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="av1bf75-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:send-outline" /></template>
<style>
.av1bf75-z {
  fill: currentColor;
  d: path("M4 18.5v-13L19.423 12zM5 17l11.85-5L5 7v3.885L9.846 12L5 13.116zm0 0V7z");
}

</style>
