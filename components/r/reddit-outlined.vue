<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmgqvvb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xmgqvvb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:reddit-outlined" /></template>
