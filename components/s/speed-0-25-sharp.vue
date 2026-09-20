<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-37qzb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-0-25-sharp" /></template>
<style>
.r-37qzb7a {
  fill: currentColor;
  d: path("M5 16.5v-1h1v1zm9 0v-1h4v-3h-4v-5h5v1h-4v3h4v5zm-6.5 0v-5h4v-3h-4v-1h5v5h-4v3h4v1z");
}

</style>
