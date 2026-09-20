<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umfyvccsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="umfyvccsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:nginx" /></template>
