<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3h8efboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i3h8efboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:prohibited" /></template>
