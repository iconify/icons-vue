<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8l6k8asg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d8l6k8asg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:strikethrough-outline" /></template>
