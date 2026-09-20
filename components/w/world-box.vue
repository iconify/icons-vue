<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve418qbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve418qbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:world-box" /></template>
