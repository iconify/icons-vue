<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxm0nzb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yxm0nzb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scan-20-bold" /></template>
