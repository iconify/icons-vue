<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fsxm7vbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rectangle-portrait-20-filled" /></template>
<style>
.fsxm7vbwq {
  fill: currentColor;
  d: path("M4 15a3 3 0 0 0 3 3h6a3 3 0 0 0 3-3V5a3 3 0 0 0-3-3H7a3 3 0 0 0-3 3z");
}

</style>
