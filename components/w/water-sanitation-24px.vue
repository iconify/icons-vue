<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws5a_qbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws5a_qbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:water-sanitation-24px" /></template>
