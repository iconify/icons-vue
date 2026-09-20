<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i43rgfbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i43rgfbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:toilet-paper" /></template>
