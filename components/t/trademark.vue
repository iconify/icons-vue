<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2at43bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l2at43bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:trademark" /></template>
