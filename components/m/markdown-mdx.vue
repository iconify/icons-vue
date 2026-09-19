<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ald7zq9it.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ald7zq9it"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:markdown-mdx" /></template>
