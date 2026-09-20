<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxdoup2oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:merge-sharp" /></template>
<style>
.fxdoup2oo {
  fill: currentColor;
  d: path("m6.4 20l-.688-.688l5.788-5.795V5.883L9.38 7.996l-.688-.688L12 4l3.308 3.308l-.689.688L12.5 5.883v7.634l5.789 5.795L17.6 20L12 14.4z");
}

</style>
