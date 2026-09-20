<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqt6r9oga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="lqt6r9oga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:word-wrap-around-bounding-box" /></template>
