<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y57xxsbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y57xxsbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:video-off-stroke-16" /></template>
