<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k193bi48h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sticky-note-2-outline-sharp" /></template>
<style>
.k193bi48h {
  fill: currentColor;
  d: path("M5 19h9v-5h5V5H5zm-1 1V4h16v10.289L14.288 20zm3.885-6.539v-1H12v1zm0-3.961v-1h8.23v1zM5 19V5z");
}

</style>
