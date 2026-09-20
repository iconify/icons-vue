<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad1opj13q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ad1opj13q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:to-do" /></template>
