<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo9gcnbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo9gcnbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-calendar-ascending" /></template>
