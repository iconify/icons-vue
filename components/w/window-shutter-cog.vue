<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5154zmty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5154zmty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:window-shutter-cog" /></template>
