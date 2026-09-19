<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_2qah0lr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r_2qah0lr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:taobao" /></template>
