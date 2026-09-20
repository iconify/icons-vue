<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfrfb91zw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfrfb91zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:smartphone" /></template>
