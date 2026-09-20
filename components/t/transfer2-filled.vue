<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh_g21kfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh_g21kfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:transfer2-filled" /></template>
