<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofhx-bc_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofhx-bc_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:water-circle" /></template>
