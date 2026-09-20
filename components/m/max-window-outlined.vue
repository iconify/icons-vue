<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjhmhrwgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjhmhrwgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:max-window-outlined" /></template>
