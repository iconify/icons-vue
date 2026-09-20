<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl_go2b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-0-5-sharp" /></template>
<style>
.fl_go2b-w {
  fill: currentColor;
  d: path("M7.75 16.5v-1h1v1zm2.5 0v-1h4v-3h-4v-5h5v1h-4v3h4v5z");
}

</style>
