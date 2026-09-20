<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8uve1u_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8uve1u_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:window-chart-line-filled" /></template>
