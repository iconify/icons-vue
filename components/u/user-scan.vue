<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqiu88m_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqiu88m_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:user-scan" /></template>
