<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn0wn_bdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cn0wn_bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:radar-chart-outlined" /></template>
