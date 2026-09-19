<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfzb2rv_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qfzb2rv_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:yahoo-filled" /></template>
