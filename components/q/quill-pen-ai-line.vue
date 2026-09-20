<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3dy2ibji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3dy2ibji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:quill-pen-ai-line" /></template>
