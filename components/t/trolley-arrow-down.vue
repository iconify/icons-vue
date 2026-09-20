<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isp18v05x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isp18v05x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:trolley-arrow-down" /></template>
