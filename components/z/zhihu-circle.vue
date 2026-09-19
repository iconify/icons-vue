<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg9d7cc2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xg9d7cc2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:zhihu-circle" /></template>
