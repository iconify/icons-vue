<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9ywjwimg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rectangle-add-sharp" /></template>
<style>
.o9ywjwimg {
  fill: currentColor;
  d: path("M11.5 15.5h1v-3h3v-1h-3v-3h-1v3h-3v1h3zM3 19V5h18v14z");
}

</style>
