<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s52488q7t.css';
import '../../css/d/d58ezqogs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s52488q7t"/><path class="d58ezqogs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:virtual-desktop" /></template>
