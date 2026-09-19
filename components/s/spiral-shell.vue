<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv6bntf8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cv6bntf8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:spiral-shell" /></template>
