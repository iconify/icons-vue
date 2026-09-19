<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqphrup5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oqphrup5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:red-question-mark" /></template>
