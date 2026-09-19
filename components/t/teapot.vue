<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_5c160_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s_5c160_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:teapot" /></template>
