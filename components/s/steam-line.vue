<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwc_y5dxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwc_y5dxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:steam-line" /></template>
