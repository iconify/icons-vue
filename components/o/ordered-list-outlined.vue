<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0bikvbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w0bikvbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:ordered-list-outlined" /></template>
