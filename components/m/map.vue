<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyu3vjbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyu3vjbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:map" /></template>
