<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy5mv509z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy5mv509z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-time-ascending" /></template>
