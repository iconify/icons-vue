<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rogl70aes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rogl70aes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:sake" /></template>
