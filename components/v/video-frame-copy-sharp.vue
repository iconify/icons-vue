<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogy-44_4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:video-frame-copy-sharp" /></template>
<style>
.ogy-44_4n {
  fill: currentColor;
  d: path("M1 21V7h2v12h16v2zM21 8V5h-3V3h5v5zM5 8V3h5v2H7v3zm13 9v-2h3v-3h2v5zM5 17v-5h2v3h3v2zm7-3l6.225-4L12 6z");
}

</style>
