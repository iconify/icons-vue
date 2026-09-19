<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5cii_bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5cii_bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:nav-arrow-down" /></template>
