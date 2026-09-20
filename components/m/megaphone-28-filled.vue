<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="sasxoqkrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:megaphone-28-filled" /></template>
<style>
.sasxoqkrc {
  fill: currentColor;
  d: path("M26 7.353a2.75 2.75 0 0 0-3.458-2.657L4.045 9.629a2.75 2.75 0 0 0-2.041 2.657v3.427a2.75 2.75 0 0 0 2.041 2.657L7 19.158v.342a4.5 4.5 0 0 0 8.56 1.942l6.982 1.862A2.75 2.75 0 0 0 26 20.647zM8.5 19.56l5.572 1.486A3 3 0 0 1 8.5 19.559");
}

</style>
