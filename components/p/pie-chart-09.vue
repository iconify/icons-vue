<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_2xg0b1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_2xg0b1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pie-chart-09" /></template>
