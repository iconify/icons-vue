<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb_kiboka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb_kiboka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:report-line-shimmer" /></template>
