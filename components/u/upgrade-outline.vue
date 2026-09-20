<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfc0ojdum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:upgrade-outline" /></template>
<style>
.dfc0ojdum {
  fill: currentColor;
  d: path("M7.5 19v-1h9v1zm4-3.384V6.883L8.38 9.996l-.688-.688L12 5l4.308 4.308l-.689.688L12.5 6.883v8.733z");
}

</style>
