<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgi3klbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hgi3klbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:message-outline" /></template>
