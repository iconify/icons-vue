<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzhm1sb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nzhm1sb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:pause-circle-filled" /></template>
