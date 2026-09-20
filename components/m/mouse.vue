<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qna1oz1fb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qna1oz1fb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:mouse" /></template>
