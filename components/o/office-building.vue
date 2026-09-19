<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry77vccoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ry77vccoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:office-building" /></template>
