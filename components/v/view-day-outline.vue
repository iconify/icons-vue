<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktj6559nw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktj6559nw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-day-outline" /></template>
