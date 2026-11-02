<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up06yedxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up06yedxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:send-plane-line" /></template>
