<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ahnd60bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:multiplication-sign" /></template>
<style>
.ahnd60bam {
  fill: var(--svg-color--31373d, #31373d);
  d: path("m22.238 18.004l9.883-9.883a3 3 0 1 0-4.242-4.243l-9.883 9.883l-9.883-9.882A3 3 0 1 0 3.87 8.122l9.883 9.882l-9.907 9.907a3 3 0 0 0 4.243 4.242l9.906-9.906l9.882 9.882c.586.586 1.354.879 2.121.879s1.535-.293 2.121-.879a3 3 0 0 0 0-4.242z");
}

</style>
