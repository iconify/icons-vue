<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1fk8ibfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:screenshot-frame-sharp" /></template>
<style>
.i1fk8ibfw {
  fill: currentColor;
  d: path("M6 7V3h4v1H7v3zm0 14v-4h1v3h3v1zM17 7V4h-3V3h4v4zm-3 14v-1h3v-3h1v4z");
}

</style>
