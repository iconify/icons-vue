<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t785xib2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t785xib2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:wine-glass" /></template>
