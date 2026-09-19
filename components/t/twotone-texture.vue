<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="luv9smb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-texture" /></template>
<style>
.luv9smb7o {
  fill: currentColor;
  d: path("M11.88 3L3 11.88v2.83L14.71 3zM3 5v2l4-4H5c-1.1 0-2 .9-2 2m16.51-1.92L3.08 19.51c.09.34.27.65.51.9c.25.24.56.42.9.51L20.93 4.49c-.19-.69-.73-1.23-1.42-1.41M21 9.29L9.29 21h2.83L21 12.12zm-.59 11.12c.37-.36.59-.86.59-1.41v-2l-4 4h2c.55 0 1.05-.22 1.41-.59");
}

</style>
