<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfoeq1bpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bfoeq1bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:record-fill" /></template>
