<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q43hrvcvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q43hrvcvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:red-question-mark" /></template>
