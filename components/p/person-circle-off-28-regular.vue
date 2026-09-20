<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="h6tmpzbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-circle-off-28-regular" /></template>
<style>
.h6tmpzbuy {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l22.5 22.5a.75.75 0 0 1-1.06 1.06l-2.784-2.784A11.95 11.95 0 0 1 14 26C7.373 26 2 20.627 2 14c0-3.044 1.134-5.822 3.002-7.937L2.22 3.28a.75.75 0 0 1 0-1.06m3.844 4.905A10.46 10.46 0 0 0 3.5 14c0 5.799 4.701 10.5 10.5 10.5c2.63 0 5.031-.97 6.873-2.566L18.61 19.67c-1.1 1.156-2.755 1.83-4.61 1.83c-3.314 0-6-2.143-6-5.357C8 14.959 8.96 14 10.143 14h2.797zM14 2c6.627 0 12 5.373 12 12c0 2.501-.767 4.823-2.076 6.745l-1.084-1.084A10.45 10.45 0 0 0 24.5 14c0-5.799-4.701-10.5-10.5-10.5c-2.086 0-4.028.61-5.662 1.66L7.254 4.074A11.94 11.94 0 0 1 14 2m3.857 12c1.184 0 2.143.96 2.143 2.143q-.001.327-.038.64L17.179 14zM14 6a3.25 3.25 0 0 1 1.374 6.195l-4.32-4.32A3.25 3.25 0 0 1 14 6");
}

</style>
