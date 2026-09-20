<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vts9yxb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vts9yxb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:map-pin-time-fill" /></template>
