<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itluvfbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itluvfbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:numbers-90-sort-descending-fill" /></template>
