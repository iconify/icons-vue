<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf0-e1b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sf0-e1b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:yuque-outlined" /></template>
