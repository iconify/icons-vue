<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yixrgx18v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yixrgx18v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pino" /></template>
