<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omviflb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="omviflb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:money-collect" /></template>
