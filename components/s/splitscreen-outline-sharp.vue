<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxib8db2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:splitscreen-outline-sharp" /></template>
<style>
.xxib8db2j {
  fill: currentColor;
  d: path("M4 10.635V4h16v6.635zm1-1h14V5H5zM4 20v-6.615h16V20zm1-1h14v-4.615H5zm0-9.365V5zM5 19v-4.615z");
}

</style>
