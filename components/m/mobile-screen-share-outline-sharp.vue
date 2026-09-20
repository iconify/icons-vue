<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwu-3bc2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-screen-share-outline-sharp" /></template>
<style>
.wwu-3bc2t {
  fill: currentColor;
  d: path("M9 15v-4.5h4v-2l3 3l-3 3v-2h-2V15zm-4 8V1h14v22zm2-3v1h10v-1zm0-2h10V6H7zM7 4h10V3H7zm0 0V3zm0 16v1z");
}

</style>
