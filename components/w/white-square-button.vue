<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpa4bib7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qpa4bib7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:white-square-button" /></template>
