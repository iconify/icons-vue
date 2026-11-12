<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl89sibfb"/><path class="nayqy1c_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rows-2-bold-duotone" /></template>
<style>
.nayqy1c_r {
  fill: currentColor;
  d: path("M13 2C16.7712 2 18.6569 2 19.8284 3.17157C21 4.34315 21 6.22876 21 10L21 14C21 17.7712 21 19.6569 19.8284 20.8284C18.6569 22 16.7712 22 13 22L11 22C7.22876 22 5.34315 22 4.17157 20.8284C3 19.6569 3 17.7712 3 14L3 10C3 6.22876 3 4.34315 4.17157 3.17157C5.34315 2 7.22876 2 11 2L13 2Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.yl89sibfb {
  fill: currentColor;
  d: path("M21 11.25L21 12.75L3 12.75L3 11.25L21 11.25Z");
}

</style>
