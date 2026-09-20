<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij60dabxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij60dabxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:map-outline" /></template>
