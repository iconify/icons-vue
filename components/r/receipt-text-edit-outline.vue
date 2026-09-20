<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_79w7bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_79w7bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:receipt-text-edit-outline" /></template>
