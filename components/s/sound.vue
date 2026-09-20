<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmpgb3bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jmpgb3bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:sound" /></template>
