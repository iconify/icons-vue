<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8c9_rbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8c9_rbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ping-pong-line" /></template>
