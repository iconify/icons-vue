<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2mzdq3zh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w2mzdq3zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:plus-square-fill" /></template>
