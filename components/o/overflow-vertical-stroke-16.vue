<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx4k27b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yx4k27b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:overflow-vertical-stroke-16" /></template>
