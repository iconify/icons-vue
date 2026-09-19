<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4p5sgccu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l4p5sgccu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:qwen-filled" /></template>
