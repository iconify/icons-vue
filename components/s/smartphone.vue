<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3p41ib4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3p41ib4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:smartphone" /></template>
