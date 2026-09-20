<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd2z5417k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tab-close-outline-sharp" /></template>
<style>
.dd2z5417k {
  fill: currentColor;
  d: path("m11.4 12.789l2.1-2.1l2.1 2.1l.688-.689l-2.1-2.1l2.1-2.1l-.688-.689l-2.1 2.1l-2.1-2.1l-.688.689l2.1 2.1l-2.1 2.1zM6.5 17V3h14v14zm1-1h12V4h-12zm-4 4V6.616h1V19h12.385v1zm4-4V4z");
}

</style>
