<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4w5c7bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y4w5c7bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:x-filled" /></template>
