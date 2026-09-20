<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_9j0qbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_9j0qbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:x-ray-box-outline" /></template>
