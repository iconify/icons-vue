<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5ct4aboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:thumb-up-sharp" /></template>
<style>
.l5ct4aboz {
  fill: currentColor;
  d: path("M8 21V8l7-7l1.85 1.85L15.55 8H23v4.4L19.35 21zm-6 0V8h4v13z");
}

</style>
