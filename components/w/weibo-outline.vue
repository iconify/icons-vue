<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq8ni5b_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yq8ni5b_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:weibo-outline" /></template>
