<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep6q_wb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep6q_wb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:menu-down" /></template>
