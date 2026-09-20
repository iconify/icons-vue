<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggy21bbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ggy21bbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:mesoamerican-pyramid" /></template>
