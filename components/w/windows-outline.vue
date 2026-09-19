<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ump_5_t_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ump_5_t_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:windows-outline" /></template>
