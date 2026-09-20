<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx3w-qynf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx3w-qynf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-3d-nozzle-alert" /></template>
