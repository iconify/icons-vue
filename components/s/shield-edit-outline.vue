<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc20-fbnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc20-fbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-edit-outline" /></template>
