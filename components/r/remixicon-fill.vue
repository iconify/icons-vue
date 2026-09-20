<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjs1y2sgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjs1y2sgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:remixicon-fill" /></template>
