<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxb2hvbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vxb2hvbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:pause-outlined" /></template>
