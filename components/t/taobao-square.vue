<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9_4cn2dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o9_4cn2dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:taobao-square" /></template>
