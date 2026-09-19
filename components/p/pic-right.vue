<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e60q68won.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e60q68won"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:pic-right" /></template>
