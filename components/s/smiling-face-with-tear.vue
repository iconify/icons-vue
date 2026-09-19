<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wkn2rtb4z.css';
import '../../css/m/m6pakbbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="wkn2rtb4z"/><path clip-rule="evenodd" class="m6pakbbbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:smiling-face-with-tear" /></template>
