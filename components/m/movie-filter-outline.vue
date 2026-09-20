<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cblcotbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cblcotbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:movie-filter-outline" /></template>
