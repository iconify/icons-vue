<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_2x2fbfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d_2x2fbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:purple-square" /></template>
