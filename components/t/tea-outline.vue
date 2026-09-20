<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w331e2k4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w331e2k4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tea-outline" /></template>
