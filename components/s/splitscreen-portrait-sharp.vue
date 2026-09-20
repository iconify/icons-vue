<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aezlwcckt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:splitscreen-portrait-sharp" /></template>
<style>
.aezlwcckt {
  fill: currentColor;
  d: path("M8 18h8v-5H8zm0-7h8V6H8zM4 22V2h16v20z");
}

</style>
