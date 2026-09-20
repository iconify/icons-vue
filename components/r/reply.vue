<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0kji3b4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i0kji3b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:reply" /></template>
