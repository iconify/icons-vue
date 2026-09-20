<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akvnb9l1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:photo-size-select-large-sharp" /></template>
<style>
.akvnb9l1a {
  fill: currentColor;
  d: path("M4 20V7.77h12.23V20zm2-2h8.23l-2.784-3.692l-2.138 2.884l-1.331-1.765zm13-.808v-2h1v2zM19 13v-2h1v2zm0-4.192v-2h1v2zM7 5V4h2v1zm4 0V4h2v1zm4 0V4h2v1zM4 5V4h1v1zm16 0h-1V4h1zm-1 15v-1h1v1z");
}

</style>
