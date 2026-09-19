<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag2uoq-ap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ag2uoq-ap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:registry-editor" /></template>
