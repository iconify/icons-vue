<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvx6_gzou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvx6_gzou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:octagon-x" /></template>
