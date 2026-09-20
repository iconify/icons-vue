<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkmxy_cyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkmxy_cyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:move-fill" /></template>
