<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1i7d-1da.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x1i7d-1da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:message-fill" /></template>
