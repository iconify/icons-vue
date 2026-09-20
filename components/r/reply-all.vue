<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc86awldh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gc86awldh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:reply-all" /></template>
