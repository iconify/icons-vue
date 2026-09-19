<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xudfxxb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xudfxxb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:vertical-align-middle-outline" /></template>
