<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysl3ccail.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysl3ccail"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:mortar-board-24" /></template>
