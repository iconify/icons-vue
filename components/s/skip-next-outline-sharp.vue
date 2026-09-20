<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l52pqtbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:skip-next-outline-sharp" /></template>
<style>
.l52pqtbvm {
  fill: currentColor;
  d: path("M16.27 16.616V7.385h1v9.23zm-9.54 0V7.385L13.655 12zm1-1.866L11.862 12l-4.13-2.75z");
}

</style>
