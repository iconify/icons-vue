<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylyopj0xj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylyopj0xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:menu-unfold-4-line" /></template>
