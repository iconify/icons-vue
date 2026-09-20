<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbkf7dqvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbkf7dqvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:monitor-lock" /></template>
