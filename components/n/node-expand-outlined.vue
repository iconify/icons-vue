<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so2_osfrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="so2_osfrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:node-expand-outlined" /></template>
