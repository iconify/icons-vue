<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivpp-d16v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:single-arrow-outline" /></template>
<style>
.ivpp-d16v {
  fill: currentColor;
  d: path("m7.775 19l5-7l-5-7h2.45l5 7l-5 7z");
}

</style>
