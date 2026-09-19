<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg5f894wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yg5f894wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:plane-take-off" /></template>
