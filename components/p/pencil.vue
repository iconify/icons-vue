<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh6cq6a0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh6cq6a0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:pencil" /></template>
