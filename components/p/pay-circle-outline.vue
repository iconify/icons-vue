<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz77wfhmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sz77wfhmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:pay-circle-outline" /></template>
