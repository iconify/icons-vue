<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umd2mhbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umd2mhbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:thermometer-fill" /></template>
