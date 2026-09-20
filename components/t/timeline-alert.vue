<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxek1-9tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxek1-9tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timeline-alert" /></template>
