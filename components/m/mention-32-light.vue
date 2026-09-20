<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aysb3xb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mention-32-light" /></template>
<style>
.aysb3xb2m {
  fill: currentColor;
  d: path("M16 2c7.732 0 14 6.268 14 14q0 .312-.016.62l-.011.233l-.003.061l-.004.02c-.124 1.79-.602 3.207-1.306 4.224c-.825 1.191-1.967 1.84-3.161 1.84s-2.335-.649-3.16-1.84c-.406-.587-.737-1.306-.969-2.154C20.331 21.354 18.112 23 15.5 23C11.873 23 9 19.828 9 16s2.873-7 6.5-7c2.335 0 4.355 1.316 5.5 3.273V9.5a.5.5 0 0 1 1 0V16c0 2.094.484 3.61 1.161 4.589c.675.974 1.532 1.409 2.338 1.409s1.664-.435 2.339-1.41c.677-.977 1.161-2.494 1.161-4.588v-.01C28.994 8.815 23.176 3 16 3C8.82 3 3 8.82 3 16s5.82 13 13 13a13 13 0 0 0 4.88-.948a.52.52 0 0 1 .565.11a.488.488 0 0 1-.15.8A14 14 0 0 1 16 30C8.268 30 2 23.732 2 16S8.268 2 16 2m-.5 8c-3 0-5.5 2.648-5.5 6s2.5 6 5.5 6s5.5-2.648 5.5-6s-2.5-6-5.5-6");
}

</style>
