<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpy387b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:scanner-outline-sharp" /></template>
<style>
.wpy387b5z {
  fill: currentColor;
  d: path("M17.985 13L4.846 8.246l.316-.938L20 12.708V19H4v-6zM19 18v-4H5v4zm-8.846-1.5H17.5v-1h-7.346zM5 18v-4zm1.23-1.23h1.54v-1.54H6.23z");
}

</style>
