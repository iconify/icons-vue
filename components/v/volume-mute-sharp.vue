<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-cu5rj5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:volume-mute-sharp" /></template>
<style>
.c-cu5rj5k {
  fill: currentColor;
  d: path("M7 15V9h4l5-5v16l-5-5z");
}

</style>
