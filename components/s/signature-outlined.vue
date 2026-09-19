<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc_g6wb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jc_g6wb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:signature-outlined" /></template>
