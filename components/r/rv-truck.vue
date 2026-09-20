<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1450-bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1450-bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rv-truck" /></template>
