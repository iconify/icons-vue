<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgi-d2aje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xgi-d2aje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:menu-fold-outline" /></template>
