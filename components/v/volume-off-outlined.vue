<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv3xjpb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv3xjpb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:volume-off-outlined" /></template>
