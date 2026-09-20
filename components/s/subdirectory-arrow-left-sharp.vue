<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8ne-k42k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:subdirectory-arrow-left-sharp" /></template>
<style>
.r8ne-k42k {
  fill: currentColor;
  d: path("m10 21l-6-6l6.025-6.025l1.4 1.425l-3.6 3.6H17V4h2v12H7.825l3.6 3.575z");
}

</style>
