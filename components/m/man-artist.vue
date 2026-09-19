<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b_np3ukdd.css';
import '../../css/d/ds3iw5z2y.css';
import '../../css/w/w4opac-us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="b_np3ukdd"/><path class="ds3iw5z2y"/><path class="w4opac-us"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:man-artist" /></template>
