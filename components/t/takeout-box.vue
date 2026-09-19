<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g0-5i-b1b.css';
import '../../css/v/vk7vg5bcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="g0-5i-b1b"/><path class="vk7vg5bcj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:takeout-box" /></template>
