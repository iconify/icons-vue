<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snt803bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="snt803bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pie-chart-solid" /></template>
