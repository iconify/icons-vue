<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev3r4g_nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev3r4g_nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:xls-line" /></template>
