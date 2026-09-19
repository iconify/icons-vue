<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz2uiw5iv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="uz2uiw5iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:zhihu-outlined" /></template>
