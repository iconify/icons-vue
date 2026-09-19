<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9nlzxm0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-file-upload" /></template>
<style>
.n9nlzxm0z {
  fill: currentColor;
  d: path("M5 10h4v6h6v-6h4l-7-7zm0 8v2h14v-2z");
}

</style>
