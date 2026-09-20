<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrgmuk__m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrgmuk__m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:window-grid" /></template>
