<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai-1qvthx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ai-1qvthx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:triangles-left-right-in-rectangle-outline" /></template>
