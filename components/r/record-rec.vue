<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx8l00b_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx8l00b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:record-rec" /></template>
