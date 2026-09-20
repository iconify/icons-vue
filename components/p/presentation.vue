<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5r6mjb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5r6mjb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:presentation" /></template>
