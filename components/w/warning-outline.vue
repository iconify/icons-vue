<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h64cczbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="h64cczbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:warning-outline" /></template>
