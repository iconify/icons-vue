<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxkyst8qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gxkyst8qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:mount-fuji" /></template>
