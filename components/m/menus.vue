<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh54k8brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh54k8brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:menus" /></template>
