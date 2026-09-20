<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg06_ub1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg06_ub1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:truck-off-road-off" /></template>
