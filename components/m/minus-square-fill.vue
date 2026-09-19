<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm4iebcjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fm4iebcjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:minus-square-fill" /></template>
