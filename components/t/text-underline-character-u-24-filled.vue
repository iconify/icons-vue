<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzsmmtegp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-underline-character-u-24-filled" /></template>
<style>
.zzsmmtegp {
  fill: currentColor;
  d: path("M9 5a1 1 0 0 0-2 0v6.5a5 5 0 0 0 10 0V5a1 1 0 1 0-2 0v6.5a3 3 0 1 1-6 0zM7 18a1 1 0 1 0 0 2h10a1 1 0 1 0 0-2z");
}

</style>
