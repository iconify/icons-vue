<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy0alfbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy0alfbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:message-circle-warning" /></template>
