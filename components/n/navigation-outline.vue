<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8g66ewnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:navigation-outline" /></template>
<style>
.w8g66ewnt {
  fill: currentColor;
  d: path("m5.962 19.5l-.462-.423L12 4.462l6.5 14.615l-.462.423L12 16.923zM7.1 17.9l4.9-2.1l4.9 2.1l-4.9-11zm4.9-2.1");
}

</style>
