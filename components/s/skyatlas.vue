<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y75ealbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y75ealbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:skyatlas" /></template>
