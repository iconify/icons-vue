<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srxy_7bjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srxy_7bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:svg" /></template>
