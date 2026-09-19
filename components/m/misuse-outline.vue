<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdl8c9zis.css';
import '../../css/y/ydhwbwb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qdl8c9zis"/><path class="ydhwbwb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:misuse-outline" /></template>
