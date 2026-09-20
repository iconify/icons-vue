<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zztj777xk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:toggle-right-16-filled" /></template>
<style>
.zztj777xk {
  fill: currentColor;
  d: path("M5 4a4 4 0 1 0 0 8h6a4 4 0 0 0 0-8zm6 6a2 2 0 1 1 0-4a2 2 0 0 1 0 4");
}

</style>
