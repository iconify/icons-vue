<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcjx7jhaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcjx7jhaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:stethoscope-24px" /></template>
