<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhd4-8i0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jhd4-8i0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:undo" /></template>
