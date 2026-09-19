<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q34wt5ikc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q34wt5ikc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:vertical-align-top-outline" /></template>
