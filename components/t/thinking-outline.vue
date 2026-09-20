<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgwgnibyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgwgnibyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:thinking-outline" /></template>
