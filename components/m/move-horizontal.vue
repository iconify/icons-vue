<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yneekqblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yneekqblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:move-horizontal" /></template>
