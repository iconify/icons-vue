<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-x_vrxce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-x_vrxce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:squats-line" /></template>
