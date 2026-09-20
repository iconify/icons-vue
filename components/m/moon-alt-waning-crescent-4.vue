<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n02m9nptx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="n02m9nptx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-alt-waning-crescent-4" /></template>
