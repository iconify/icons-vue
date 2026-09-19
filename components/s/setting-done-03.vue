<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zqbtg_noo.css';
import '../../css/k/kis3z9bum.css';
import '../../css/s/sg3by7iou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zqbtg_noo"/><path class="kis3z9bum"/><path class="sg3by7iou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:setting-done-03" /></template>
