<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqt12ccgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:weekend-sharp" /></template>
<style>
.kqt12ccgr {
  fill: currentColor;
  d: path("M4.615 15.423V9.231h-.384v-1.5h15.538v1.5h-.384v6.192zm-1.23 2.192V9.308h1.384v2.961h14.462V9.308h1.384v8.307z");
}

</style>
