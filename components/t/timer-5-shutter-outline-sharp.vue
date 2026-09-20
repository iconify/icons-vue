<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hag7awbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:timer-5-shutter-outline-sharp" /></template>
<style>
.hag7awbyq {
  fill: currentColor;
  d: path("M8.885 18.116v-1.231h6v-4.27h-6v-6.73h7.23v1.23h-6v4.27h6v6.73z");
}

</style>
