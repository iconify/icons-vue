<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mloygh_vd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mloygh_vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:receipt-text-plus" /></template>
