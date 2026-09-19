<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikc3oob9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ikc3oob9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:pinterest-outlined" /></template>
