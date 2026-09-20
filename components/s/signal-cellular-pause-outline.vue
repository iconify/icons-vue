<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0_t3qb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-cellular-pause-outline" /></template>
<style>
.d0_t3qb1t {
  fill: currentColor;
  d: path("M2 22L22 2v11h-2V6.825L6.825 20H13v2zm13 0v-7h2v7zm4 0v-7h2v7zm-5.575-8.6");
}

</style>
