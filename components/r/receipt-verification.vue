<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk8zi3b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zk8zi3b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:receipt-verification" /></template>
