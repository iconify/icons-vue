<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd5kx9nig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vd5kx9nig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:taobao-circle-outline" /></template>
