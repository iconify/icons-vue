<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/ch5uyed_k.css';
import '../../css/f/f7aqdaclx.css';
import '../../css/q/qvngzn1zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="ch5uyed_k"/><path class="f7aqdaclx"/><path class="qvngzn1zn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:video-camera" /></template>
