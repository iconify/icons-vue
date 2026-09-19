<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9hnr1bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x9hnr1bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:rise-outlined" /></template>
