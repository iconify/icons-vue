<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dyhrp6boo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:select-object-skew-16-filled" /></template>
<style>
.dyhrp6boo {
  fill: currentColor;
  d: path("M2.5 11a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m8 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m-2.29.5a2.5 2.5 0 0 0-.16 1.5h-3.1a2.5 2.5 0 0 0-.16-1.5zM4.07 5.549c.406.283.898.451 1.43.451l.001-.001l-1.571 4.452A2.5 2.5 0 0 0 2.5 10zm8 0c.406.283.898.451 1.43.451l.002-.001l-1.571 4.452A2.5 2.5 0 0 0 10.5 10zM5.5 2a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m8 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m-2.45 1a2.5 2.5 0 0 0 .16 1.5H7.79A2.5 2.5 0 0 0 7.95 3z");
}

</style>
