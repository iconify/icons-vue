<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di9d21bpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="di9d21bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:search" /></template>
