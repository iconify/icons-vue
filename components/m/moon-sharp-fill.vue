<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irzbusbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:moon-sharp-fill" /></template>
<style>
.irzbusbos {
  fill: currentColor;
  d: path("M22 12C22 17.3848 17.3848 22 12 22C6.6152 22 2 17.3848 2 12C2 6.6152 6.6152 2 12 2C12.8385 2 13.3047 2.9699 12.7809 3.6247C10.9814 5.874 11.1425 8.7837 13.1794 10.8206C15.2163 12.8575 18.126 13.0186 20.3753 11.2191C21.0301 10.6953 22 11.1615 22 12Z");
}

</style>
