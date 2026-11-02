<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyfe3abty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyfe3abty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:refund-dollar-line" /></template>
