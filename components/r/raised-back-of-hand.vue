<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyq7z9z1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xyq7z9z1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:raised-back-of-hand" /></template>
