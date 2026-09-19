<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guz3d-buf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="guz3d-buf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:wechat-work-outlined" /></template>
