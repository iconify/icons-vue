<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnwz1hbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnwz1hbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:temple-of-heaven-line" /></template>
