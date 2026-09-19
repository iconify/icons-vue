<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz8w-qbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fz8w-qbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:white-question-mark" /></template>
