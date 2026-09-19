<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrdb7tbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yrdb7tbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:task-hold" /></template>
