<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujmq1_hwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujmq1_hwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:typewriter" /></template>
