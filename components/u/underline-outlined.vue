<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_9_k6c_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="h_9_k6c_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:underline-outlined" /></template>
