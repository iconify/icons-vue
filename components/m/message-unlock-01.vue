<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/ti43njbxy.css';
import '../../css/u/uwvkzmbgi.css';
import '../../css/c/cygy2y6yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ti43njbxy"/><path class="uwvkzmbgi"/><path class="cygy2y6yc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:message-unlock-01" /></template>
