<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4jsplqjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n4jsplqjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:node-index" /></template>
