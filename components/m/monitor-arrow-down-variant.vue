<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlikc8b7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlikc8b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:monitor-arrow-down-variant" /></template>
