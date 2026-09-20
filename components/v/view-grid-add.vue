<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxh2jebzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxh2jebzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-grid-add" /></template>
