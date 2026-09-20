<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulx72ubuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulx72ubuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:microsoft-excel" /></template>
