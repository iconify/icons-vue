<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh1userbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh1userbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:medical-cross" /></template>
