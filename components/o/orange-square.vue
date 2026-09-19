<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2rvh9ety.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u2rvh9ety"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:orange-square" /></template>
