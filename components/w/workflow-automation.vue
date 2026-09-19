<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auo3ycdia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="auo3ycdia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:workflow-automation" /></template>
