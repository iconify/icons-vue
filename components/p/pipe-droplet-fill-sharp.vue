<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-htcm06i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pipe-droplet-fill-sharp" /></template>
<style>
.j-htcm06i {
  fill: currentColor;
  d: path("M8 2a1 1 0 0 1 .832.445l2 3a1 1 0 0 1 0 1.11l-2 3A1 1 0 0 1 8 10H3a1 1 0 0 1 0-2h4.465l1.333-2l-1.333-2H3a1 1 0 0 1 0-2Zm8.535 2l-1.333 2l1.333 2H21a1 1 0 0 1 0 2h-5a1 1 0 0 1-.832-.445l-2-3a1 1 0 0 1 0-1.11l2-3A1 1 0 0 1 16 2h5a1 1 0 0 1 0 2ZM12.8 12.4l3 4a1 1 0 0 1 .2.6c0 .587-.106 1.174-.342 1.713C15.021 20.169 13.563 21 12 21a4.3 4.3 0 0 1-1.437-.245c-.99-.353-1.798-1.074-2.221-2.042A4.3 4.3 0 0 1 8 17a1 1 0 0 1 .2-.6l3-4a1 1 0 0 1 1.6 0");
}

</style>
