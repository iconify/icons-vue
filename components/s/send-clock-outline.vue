<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgxoh_b3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgxoh_b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:send-clock-outline" /></template>
