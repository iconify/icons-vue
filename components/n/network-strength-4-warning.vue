<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3ucuab8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3ucuab8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:network-strength-4-warning" /></template>
