<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atf6csb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:transition-slide-outline-sharp" /></template>
<style>
.atf6csb1k {
  fill: currentColor;
  d: path("M2 19V5h5.039v14zm1-.975h3.039V5.975H3zM9.423 19V5H22v14zm1-.975H21V5.975H10.423zm-4.384 0V5.975zm4.384 0V5.975z");
}

</style>
