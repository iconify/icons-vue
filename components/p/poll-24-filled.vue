<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni78j3hjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:poll-24-filled" /></template>
<style>
.ni78j3hjp {
  fill: currentColor;
  d: path("M11.752 2a2.75 2.75 0 0 1 2.752 2.752V19.25a2.752 2.752 0 1 1-5.504 0V4.752A2.75 2.75 0 0 1 11.752 2m7 5a2.75 2.75 0 0 1 2.752 2.752v9.498a2.752 2.752 0 1 1-5.504 0V9.752A2.75 2.75 0 0 1 18.752 7m-14 5a2.75 2.75 0 0 1 2.752 2.752v4.498a2.752 2.752 0 0 1-5.504 0v-4.498A2.75 2.75 0 0 1 4.752 12");
}

</style>
