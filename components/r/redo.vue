<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_q0zpzrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_q0zpzrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:redo" /></template>
