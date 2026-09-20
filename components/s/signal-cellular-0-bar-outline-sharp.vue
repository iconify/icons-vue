<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zeyzhjsft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-cellular-0-bar-outline-sharp" /></template>
<style>
.zeyzhjsft {
  fill: currentColor;
  d: path("M2 22L22 2v20zm4.825-2H20V6.85z");
}

</style>
