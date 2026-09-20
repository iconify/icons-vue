<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7-1racoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7-1racoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:route-square-filled" /></template>
