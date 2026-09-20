<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjhj_nbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjhj_nbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rhombus-medium-outline" /></template>
