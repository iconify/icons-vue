<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih5pgw5db.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih5pgw5db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:motion-play" /></template>
