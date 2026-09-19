<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt7yneton.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qt7yneton"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:task-blank" /></template>
