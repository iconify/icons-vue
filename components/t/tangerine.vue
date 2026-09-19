<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxoeqw4ry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sxoeqw4ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:tangerine" /></template>
