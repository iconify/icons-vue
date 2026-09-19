<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/attc-db7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="attc-db7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:up-outline" /></template>
