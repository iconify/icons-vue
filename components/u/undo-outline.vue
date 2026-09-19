<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtac5svox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vtac5svox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:undo-outline" /></template>
