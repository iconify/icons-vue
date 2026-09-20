<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj11ntbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nj11ntbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:scroll-outline" /></template>
