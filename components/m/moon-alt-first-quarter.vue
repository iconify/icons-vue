<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u99kuibgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="u99kuibgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-alt-first-quarter" /></template>
