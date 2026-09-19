<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy7x08bdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":432};
const content = `<path class="vy7x08bdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:thumb-down" /></template>
