<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8-fn9hwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f8-fn9hwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:right-square-fill" /></template>
