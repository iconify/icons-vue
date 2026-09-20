<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra7ho36rp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra7ho36rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:paper-airplane-outline" /></template>
