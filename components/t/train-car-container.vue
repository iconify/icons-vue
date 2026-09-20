<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqd5ycvcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqd5ycvcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:train-car-container" /></template>
