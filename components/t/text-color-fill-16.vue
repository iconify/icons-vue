<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlr8r5bfe.css';
import '../../css/y/yt28hwmoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zlr8r5bfe"/><path class="yt28hwmoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:text-color-fill-16" /></template>
