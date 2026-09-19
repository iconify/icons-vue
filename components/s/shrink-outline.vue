<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmnb7-83l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zmnb7-83l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:shrink-outline" /></template>
