<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmv-sxkjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nmv-sxkjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:sign-of-the-horns" /></template>
