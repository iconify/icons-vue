<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilhqy3baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-pan-tool-alt" /></template>
<style>
.ilhqy3baw {
  fill: currentColor;
  d: path("M20.18 13.4L19.1 21h-9L5 15.62l1.22-1.23l3.78.85V4.5c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5v6h1.38z");
}

</style>
