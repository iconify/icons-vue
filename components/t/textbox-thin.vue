<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jwqeemhst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:textbox-thin" /></template>
<style>
.jwqeemhst {
  fill: currentColor;
  d: path("M112 44a4 4 0 0 0-4 4v20H24a12 12 0 0 0-12 12v96a12 12 0 0 0 12 12h84v20a4 4 0 0 0 8 0V48a4 4 0 0 0-4-4M24 180a4 4 0 0 1-4-4V80a4 4 0 0 1 4-4h84v104ZM244 80v96a12 12 0 0 1-12 12h-88a4 4 0 0 1 0-8h88a4 4 0 0 0 4-4V80a4 4 0 0 0-4-4h-88a4 4 0 0 1 0-8h88a12 12 0 0 1 12 12M84 112a4 4 0 0 1-4 4H68v28a4 4 0 0 1-8 0v-28H48a4 4 0 0 1 0-8h32a4 4 0 0 1 4 4");
}

</style>
