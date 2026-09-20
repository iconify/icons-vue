<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh80lrzhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh80lrzhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:number-8-box" /></template>
