<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p41v2tb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p41v2tb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:window-shutter" /></template>
