<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md62t3byp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="md62t3byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:presentation-chart-bar" /></template>
