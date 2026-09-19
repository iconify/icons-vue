<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di220krrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="di220krrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:type-h1" /></template>
