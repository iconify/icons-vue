<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7_w19b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7_w19b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timeline-check-outline" /></template>
