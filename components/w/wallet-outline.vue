<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bseuxbb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bseuxbb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:wallet-outline" /></template>
