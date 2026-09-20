<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbtaooo4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:money-outline-sharp" /></template>
<style>
.hbtaooo4z {
  fill: currentColor;
  d: path("M14.27 15.5h3.96v-7h-3.96zm1-1v-5h1.96v5zm-6.732 1H12.5v-7H8.539zm1-1v-5H11.5v5zm-3.769 1h1v-7h-1zM3 19V5h18v14zM4 6v12zm0 12h16V6H4z");
}

</style>
