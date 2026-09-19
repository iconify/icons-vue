<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-zt0ibhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w-zt0ibhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:pic-center-outline" /></template>
