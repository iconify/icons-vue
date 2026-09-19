<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dke6q4bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dke6q4bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:question" /></template>
