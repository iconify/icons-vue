<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jko8f0oqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="jko8f0oqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-21" /></template>
