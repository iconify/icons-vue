<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8lzn6bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="e8lzn6bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:tablet" /></template>
