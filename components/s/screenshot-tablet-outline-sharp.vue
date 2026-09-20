<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="keqz_5spf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:screenshot-tablet-outline-sharp" /></template>
<style>
.keqz_5spf {
  fill: currentColor;
  d: path("M1 20V4h22v16zM4 6H3v12h1zm2 12h12V6H6zM20 6v12h1V6zm0 0h1zM4 6H3zm9 11h4v-4h-1.5v2.5H13zm-6-6h1.5V8.5H11V7H7z");
}

</style>
