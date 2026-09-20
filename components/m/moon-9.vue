<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoq3slb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="uoq3slb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-9" /></template>
